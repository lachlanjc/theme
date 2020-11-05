# @hackersent/theme

[Theme UI](https://theme-ui.com) theme for [Hackersent](https://hackersent.com)

```bash
npm i @hackersent/theme
# yarn add @hackersent/theme
```

<!-- Check out theme: [**theme.hackersent.com**](https://theme.hackersent.com) -->

## Usage

```js
import { ThemeProvider } from 'theme-ui'
import theme from '@hackersent/theme'

export default ({ children }) => (
  <ThemeProvider theme={theme}>{children}</ThemeProvider>
)
```

### Fonts

This package also bundles a CSS fils that include Hackersent's webfonts: `family.css`.
To use, just import straight from the package:

```js
import '@hackersent/theme/fonts/family.css'
```

(In a Next.js project, [place](https://nextjs.org/docs/basic-features/built-in-css-support) in the `pages/_app.js` file.)

MIT License
