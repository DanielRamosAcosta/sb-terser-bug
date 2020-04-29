## How this project was created:

1. `npx create-next-app`
2. `npx -p @storybook/cli sb init`

To provoke the error: `npm run build-storybook`

Error output: 

```
> sbtest@0.1.0 build-storybook E:\Documentos\Trabajo\Acid Tango\Libeen\sbtest
> build-storybook

info @storybook/react v5.3.18
info
info clean outputDir..
info => Copying prebuild dll's..
info => Building manager..
info => Loading manager config..
info => Loading presets
info => Compiling manager..
ERR! => Failed to build the manager
ERR! vendors~main.f255fd5eb8416a93fef7.bundle.js from Terser
ERR! undefined
(node:22996) UnhandledPromiseRejectionWarning: [object Object]
(node:22996) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 1)
(node:22996) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! sbtest@0.1.0 build-storybook: `build-storybook`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the sbtest@0.1.0 build-storybook script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\danie\AppData\Roaming\npm-cache\_logs\2020-04-29T10_06_55_123Z-debug.log
```
