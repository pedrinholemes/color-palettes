# Welcome to Trend Colors 👋

[![Version](https://img.shields.io/github/package-json/v/pedrinholemes/trend-colors?cacheSeconds=36000)](package.json)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Twitter: pedrinho_lemes](https://img.shields.io/twitter/follow/pedrinho_lemes.svg?style=social)](https://twitter.com/pedrinho_lemes)

> Color palettes for your project with react and styled-components

### 🏠 [Homepage](https://github.com/pedrinholemes/trend-colors)

## How to use

### styles/theme.js

```js
import { MaterialUiPalette, ChakraUiPalette } from "trend-colors";

const theme = {
  ...ChakraUiPalette,
  primary: "#83c9f4",
  secondary: "#6f73d2",
  fore: "#1d2135",
  back: "#d9f0ff",
};
export default theme;
```

### App.js

```jsx
import { ThemeProvider } from "styled-components";
import theme from "./styles/theme";
import GlobalStyle from "./styles/global";

function App({ children }) {
  return (
    <ThemeProvider theme={theme}>
      <GlobalStyle />
      {children}
    </ThemeProvider>
  );
}
```

## Author

👤 **Pedro Henrique**

- Website: <https://pedrinholemes.web.app>
- Twitter: [@pedrinho_lemes](https://twitter.com/pedrinho_lemes)
- Github: [@pedrinholemes](https://github.com/pedrinholemes)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check [issues page](https://github.com/pedrinholemes/trend-colors/issues). You can also take a look at the [contributing guide](#).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Pedro Henrique](https://github.com/pedrinholemes).

This project is [MIT](LICENSE) licensed.

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
