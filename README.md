# system-font-stack

[![volkswagen status](https://auchenberg.github.io/volkswagen/volkswargen_ci.svg?v=1)](https://github.com/auchenberg/volkswagen)

Use the system font family so your web app look more native

Inspired by https://css-tricks.com/snippets/css/system-font-stack/

It works really well with CSS-in-JS style solutions, like [styled-components](https://github.com/styled-components):

```js
import { injectGlobal } from 'styled-components'
import systemFontStack from 'system-font-stack'

injectGlobal`
  body {
    font-family: ${systemFontStack};
  }
`
```
