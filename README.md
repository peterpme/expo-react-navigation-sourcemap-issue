# expo sdk48 source map issue

By including a React Navigation (Tab Navigator), we are faced with a 
"Failed to parse source map from sourcemap" error

```
WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/Header.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/Header.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/Header.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/HeaderBackButton.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderBackButton.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderBackButton.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/HeaderBackContext.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderBackContext.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderBackContext.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/HeaderBackground.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderBackground.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderBackground.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/HeaderHeightContext.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderHeightContext.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderHeightContext.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/HeaderShownContext.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderShownContext.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderShownContext.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/HeaderTitle.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderTitle.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/HeaderTitle.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/getDefaultHeaderHeight.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/getDefaultHeaderHeight.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/getDefaultHeaderHeight.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/getHeaderTitle.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/getHeaderTitle.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/getHeaderTitle.tsx'

WARNING in ./node_modules/@react-navigation/elements/lib/module/Header/useHeaderHeight.js
Module Warning (from ./node_modules/source-map-loader/dist/cjs.js):
Failed to parse source map from '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/useHeaderHeight.tsx' file: Error: ENOENT: no such file or directory, open '/Users/peter/Projects/sourcemap-issue/node_modules/@react-navigation/elements/lib/src/useHeaderHeight.tsx'

```
