<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/kbram/aes-encryption-unlimited">
    <img src="https://github.com/kbram/files/blob/main/encryption-icon.png" alt="Logo" width="160" height="160">
  </a>

  <h3 align="center">aes-encryption-unlimited</h3>

  <p align="center">
    Unlimited String AES encryption and decryption with key
    <br />
    <a href="https://github.com/kbram/aes-encryption-unlimited"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/kbram/aes-encryption-unlimited">View Demo</a>
    ·
    <a href="https://github.com/kbram/aes-encryption-unlimited/issues">Report Bug</a>
    ·
    <a href="https://github.com/kbram/aes-encryption-unlimited/issues">Request Feature</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
   <li><a href="#about-project">About Project</a></li>
   <li><a href="#features">Features</a></li>
    <li><a href="#framework-support">Framework support</a></li>
    <li><a href="#built-With">Built With</a></li>
    <li>
      <a href="#get-started">Get Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usages</a></li>
    <li><a href="#options">Options</a></li>
    <li><a href="#callArrays">CallArrays</a></li>
    <li><a href="#browser-support">Browser Support</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- PROJECT FEATHERS -->
## About Project

[![](https://github.com/kbram/files/blob/main/half-pie.png)](https://github.com/kbram/files/blob/main/half-pie.png)


This UI kit is simply represent ratio of two values with the pie chart. It's fully worked on react Js. In this graph is customizable, you can change color, text, font-style,back color. You can get percentage of ratio in center part.

<p align="right">(<a href="#top">back to top</a>)</p>

## Features

  * AES-unlimited encryption without key
  * AES-unlimited decryption without key
  * AES-unlimited encryption with key
  * AES-unlimited decryption with key

<p align="right">(<a href="#top">back to top</a>)</p>

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 0.10 or higher is required.

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

Using npm:

```bash
$ npm i aes-encryption-unlimited
```

Using yarn:

```bash
$ yarn add aes-encryption-unlimited
```

<p align="right">(<a href="#top">back to top</a>)</p>

------

## Usage

```js
import AesEncryption from "aes-encryption-unlimited";


//WithoutKey
const encrypted = AesEncryption.encrypt("abc")}
const decrypted = AesEncryption.decrypt("U2FsdGVkX1+FGzP1ArvVkbieWzCb7KVNDFbSM079+N4=")

console.log('encrypted >>>>>>', encrypted)
console.log('decrypted >>>>>>', decrypted)

//WithKey
// Note: secretKey can be unlimited letters
const encrypted = AesEncryption.encrypt("abc","passKey")}
const decrypted = AesEncryption.decrypt("U2FsdGVkX1+y7iF88r8Oohony7VDFCzmvmP3t9cns7w=","passKey")

console.log('encrypted >>>>>>', encrypted)
console.log('decrypted >>>>>>', decrypted)

//inner html
 <p>{AesEncryption.encrypt("abc")}</p>
 <p>{AesEncryption.decrypt("U2FsdGVkX1+FGzP1ArvVkbieWzCb7KVNDFbSM079+N4=")}</p>
 
```

<p align="right">(<a href="#top">back to top</a>)</p>

## License

  [MIT](LICENSE)

---

>
> Developed by [`Karunaaharan Bavaram`](https://www.bavaram.info)

<p align="right">(<a href="#top">back to top</a>)</p>

## Copyright

Copyright (c) 2022 [`Karunaaharan Bavaram`](https://www.bavaram.info), contributors. Released under the MIT, GPL licenses

<p align="right">(<a href="#top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/kbram/aes-encryption-unlimited.svg?style=for-the-badge
[contributors-url]: https://github.com/kbram/aes-encryption-unlimited/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/kbram/aes-encryption-unlimited.svg?style=for-the-badge
[forks-url]: https://github.com/kbram/aes-encryption-unlimited/network/members
[stars-shield]: https://img.shields.io/github/stars/kbram/aes-encryption-unlimited.svg?style=for-the-badge
[stars-url]: https://github.com/kbram/aes-encryption-unlimited/stargazers
[issues-shield]: https://img.shields.io/github/issues/kbram/aes-encryption-unlimited.svg?style=for-the-badge
[issues-url]: https://github.com/kbram/aes-encryption-unlimited/issues
[license-shield]: https://img.shields.io/github/license/kbram/aes-encryption-unlimited.svg?style=for-the-badge
[license-url]: https://github.com/kbram/aes-encryption-unlimited/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/bavaram
