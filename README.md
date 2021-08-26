<h1 align="center">Welcome to @kazura/tinymce 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/@kazura/tinymce" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/@kazura/tinymce.svg">
  </a>
  <a href="https://github.com/kazura233/tinymce/blob/master/LICENSE" target="_blank">
    <img alt="License" src="https://img.shields.io/npm/l/@kazura/tinymce.svg?color=blue" />
  </a>
</p>

>  由于现在 [tinymce](https://github.com/tinymce/tinymce) 官方的cdn在大陆地区表现并不理想，而且lang没有cdn，所以创建一个npm包，让lang支持cdn，并且优化在大陆地区的网络表现。没有做代码改动。

### 🏠 [Homepage](https://github.com/kazura233/tinymce)

## Usage

```html
<script src="https://cdn.jsdelivr.net/npm/@kazura/tinymce@5.8.1/tinymce.min.js"></script>
```

```javascript
tinymce.init({
  selector: "textarea", // change this value according to your HTML
  language: "zh_CN", // select language
  language_url: "https://cdn.jsdelivr.net/npm/@kazura/tinymce@5.8.1/langs/zh_CN.js" // site absolute URL
});
```

## Author

👤 **kazura233**

- Website: https://github.com/kazura233
- Github: [@kazura233](https://github.com/kazura233)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/kazura233/tinymce/issues).

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
