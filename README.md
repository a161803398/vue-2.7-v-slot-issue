Run `npm run dev` and then open dev url http://127.0.0.1:5173/ in browser given following error.

```
Invalid shorthand property initializer. (1:7)
[vite] Internal server error: Invalid shorthand property initializer. (1:7)
  Plugin: vite:vue2
  File: C:/Users/user/Desktop/v-slot-issue/src/App.vue
  1  |  <script setup lang="ts">
     |         ^
  2  |  import Test from './Test.vue'
  3  |  </script>
      at instantiate (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:72:32)
      at constructor (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:359:12)
      at Object.raise (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:3339:19)
      at Object.checkExpressionErrors (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:4083:12)
      at Object.parseMaybeAssign (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:12359:12)
      at Object.parseMaybeAssign (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:10730:20)
      at Object.parseExpressionBase (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:12257:23)
      at C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:12251:39
      at Object.allowInAnd (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:14346:16)
      at Object.parseExpression (C:\Users\user\Desktop\v-slot-issue\node_modules\@babel\parser\lib\index.js:12251:17)
```
