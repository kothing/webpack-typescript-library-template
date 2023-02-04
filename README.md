# Typescript Library Boilerplate

Minimal Library Starter Kit for your Typescript projects

## ⭐️ Features

- Webpack 5
- Babel 7
- Hot reloading (`npm start`)
- Automatic Types file generation (index.d.ts)
- UMD exports, so your library works everywhere.
- Jest unit testing
- Customizable file headers for your build

## 📦 Getting Started

```
git clone https://github.com/meta-explore/typescript-library-boilerplate.git
npm install
```

## 💎 Customization

> Before shipping, make sure to:

1. Edit `LICENSE` file
2. Edit `package.json` information (These will be used to generate the headers for your built files)
3. Edit `library: "MyLibrary"` with your library's export name in `./webpack.config.js`

## 🚀 Deployment

1. `npm publish`
2. Your users can include your library as usual

### npm

```
import MyLibrary from 'my-library';
const libraryInstance = new MyLibrary();
...
```

### self-host/cdn

```
<script src="build/index.js"></script>

const MyLibrary = window.MyLibrary.default;
const libraryInstance = new MyLibrary();
...
```

## ✅ Libraries built with this boilerplate

> Made a library using this starter kit? Share it here by [submitting a pull request](https://github.com/meta-explore/typescript-library-boilerplate/pulls)!

- [Next-Tooltip](https://github.com/meta-explore/next-tooltip) - Next-Tooltip
