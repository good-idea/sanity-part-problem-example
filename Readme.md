Running `sanity start` produces:

```
yarn run v1.13.0
$ sanity start
✔ Checking configuration files...
⠋ Compiling...webpack built 1f3c741dc806476704f4 in 44390ms
✔ Compiling...
Failed to compile.

Error in ./node_modules/@sanity/default-layout/lib/defaultLayoutRouter.js
Module not found: Error: Can't resolve 'all:part:@sanity/base/tool' in '/Users/joseph/Sites/temp/sanity-part-problem-example/sanity/node_modules/@sanity/default-layout/lib'
 @ ./node_modules/@sanity/default-layout/lib/defaultLayoutRouter.js 9:35-72
 @ ./node_modules/@sanity/default-layout/lib/components/DefaultLayoutContainer.js (part:@sanity/base/root)
 @ ./node_modules/@sanity/base/lib/components/SanityRoot.js (part:@sanity/base/sanity-root)
 @ ./node_modules/@sanity/server/lib/browser/entry-dev.js
 @ multi ./node_modules/react-hot-loader/patch.js ./node_modules/normalize.css/normalize.css ./node_modules/@sanity/server/lib/browser/entry-dev.js

Error in ./node_modules/@sanity/default-layout/lib/components/RenderTool.js
Module not found: Error: Can't resolve 'all:part:@sanity/base/tool' in '/Users/joseph/Sites/temp/sanity-part-problem-example/sanity/node_modules/@sanity/default-layout/lib/components'
 @ ./node_modules/@sanity/default-layout/lib/components/RenderTool.js 12:35-72
 @ ./node_modules/@sanity/default-layout/lib/components/DefaultLayout.js
 @ ./node_modules/@sanity/default-layout/lib/components/DefaultLayoutContainer.js (part:@sanity/base/root)
 @ ./node_modules/@sanity/base/lib/components/SanityRoot.js (part:@sanity/base/sanity-root)
 @ ./node_modules/@sanity/server/lib/browser/entry-dev.js
 @ multi ./node_modules/react-hot-loader/patch.js ./node_modules/normalize.css/normalize.css ./node_modules/@sanity/server/lib/browser/entry-dev.js

Error in ./node_modules/@sanity/default-layout/lib/util/getOrderedTools.js
Module not found: Error: Can't resolve 'all:part:@sanity/base/tool' in '/Users/joseph/Sites/temp/sanity-part-problem-example/sanity/node_modules/@sanity/default-layout/lib/util'
 @ ./node_modules/@sanity/default-layout/lib/util/getOrderedTools.js 10:35-72
 @ ./node_modules/@sanity/default-layout/lib/components/DefaultLayoutContainer.js (part:@sanity/base/root)
 @ ./node_modules/@sanity/base/lib/components/SanityRoot.js (part:@sanity/base/sanity-root)
 @ ./node_modules/@sanity/server/lib/browser/entry-dev.js
 @ multi ./node_modules/react-hot-loader/patch.js ./node_modules/normalize.css/normalize.css ./node_modules/@sanity/server/lib/browser/entry-dev.js
```
