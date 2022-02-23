# aes-encryption-react

Unlimited String AES encryption and decryption with keys 

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 0.10 or higher is required.

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

Using npm:

```bash
$ npm install aes-encryption-react
```

Using yarn:

```bash
$ yarn add aes-encryption-react
```

## Features

  * AES-unlimited encryption without key
  * AES-unlimited decryption without key
  * AES-unlimited encryption with key
  * AES-unlimited decryption with key

------

## Usage

```js
import AesEncryption from "aes-encryption-react";


//WithoutKey
const encrypted = AesEncryption.encrypt("abc","passKey")}
const decrypted = AesEncryption.decrypt("U2FsdGVkX19UMzTQ2ZzHlQCs7bfOzg/34fIfqvN4QRE=","passKey")

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
 <p>{AesEncryption.decrypt("U2FsdGVkX19UMzTQ2ZzHlQCs7bfOzg/34fIfqvN4QRE=")}</p>
 
```



## License

  [MIT](LICENSE)

---

#### *Created by CODEMONDAY's Developers Team*
