Install depedencies:
`yarn`

run `yarn format` which fails with:
```
 yarn ⮀ ✈ ⮀  yarn format
yarn run v1.17.3
$ wasc-tools format
Command failed with the following error:

Error: spawn /home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/node_modules/.bin/prettier ENOENT
    at Process.ChildProcess._handle.onexit (internal/child_process.js:248:19)
    at onErrorNT (internal/child_process.js:431:16)
    at processTicksAndRejections (internal/process/task_queues.js:84:17) {
  errno: 'ENOENT',
  code: 'ENOENT',
  syscall: 'spawn ' +
    '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/node_modules/.bin/prettier',
  path: '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/node_modules/.bin/prettier',
  spawnargs: [
    '--write',
    '--config',
    '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/config/.prettierrc.json',
    '--ignore-path',
    '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/config/.ignore',
    './**/*.{js,json,graphql,md,html}'
  ],
  stdout: null,
  stderr: null,
  failed: true,
  signal: null,
  cmd: '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/node_modules/.bin/prettier ' +
    '--write --config ' +
    '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/config/.prettierrc.json ' +
    '--ignore-path ' +
    '/home/nick/.cache/yarn/v4/npm-@wasc-tools-2.0.0-beta.2-54218b6c51a7c3d2833f1e23d8fccd5d64a40fe8/node_modules/@wasc/tools/config/.ignore ' +
    './**/*.{js,json,graphql,md,html}',
  timedOut: false,
  killed: false
}
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
