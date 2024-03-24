<h1 align="center">Welcome to One Dionys - Image Compression Tools! 👋 </h1>

<p align="center">Tools to dynamically compress images on the client side, improving performance and page load speed. 💖 </p>

<p align="center">
<img src="https://img.shields.io/github/contributors/onedionys/onedionys-image-compression-tools?style=flat-square">
<img src="https://img.shields.io/github/issues/onedionys/onedionys-image-compression-tools?style=flat-square">
<img src="https://img.shields.io/github/stars/onedionys/onedionys-image-compression-tools?style=flat-square"> 
<img src="https://img.shields.io/github/forks/onedionys/onedionys-image-compression-tools?style=flat-square">
<img src="https://img.shields.io/github/last-commit/onedionys/onedionys-image-compression-tools.svg?style=flat-square">
<img src="https://img.shields.io/github/languages/code-size/onedionys/onedionys-image-compression-tools?style=flat-square">
<img src="https://img.shields.io/github/license/onedionys/onedionys-image-compression-tools?style=flat-square">
</p>

## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const { compressImage } = require('image-compression-tools');

// Compress an image
const inputImagePath = 'path/to/input/image.jpg';
const outputImagePath = 'path/to/output/compressed-image.jpg';
const quality = 0.5; // Range: 0 to 1
compressImage(inputImagePath, outputImagePath, quality)
  .then(() => {
    console.log('Image compressed successfully!');
  })
  .catch((error) => {
    console.error('Error compressing image:', error);
  });
```

#### Explanation

* This package provides a simple API to compress images. It accepts an input image path, output image path, and quality parameter. The quality parameter ranges from 0 to 1, where 0 represents the lowest quality and 1 represents the highest quality.

#### Return Value

* `Promise`: The promise resolves when the image compression process is completed successfully, or rejects with an error if the compression fails.

## 📆 Release Date

* v1.0.0 : 17 March 2024
* v1.0.1 : 18 March 2024
* v1.0.2 : 24 March 2024

## 🧑 Author

* Facebook : <a href="https://www.facebook.com/theonedionys"> Oned Ionys</a>
* Instagram : <a href="https://www.instagram.com/onedionys/"> @onedionys</a>
* Twitter : <a href="https://twitter.com/onedionys"> @onedionys</a>
* LinkedIn :  <a href="https://www.linkedin.com/in/onedionys/"> @onedionys</a>

## 📝 License

* Copyright © 2024 One Dionys
* **One Dionys - Image Compression Tools is an open source project licensed under the MIT license**

## ☕️ Suppport & Donation

Love One Dionys - Image Compression Tools? Support this project by donating or sharing with others in need.

<a href="https://www.buymeacoffee.com/onedionys"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black"/> </a>

**Made with ❤️ One Dionys**
