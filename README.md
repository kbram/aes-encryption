# aes-encryption-unlimited

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
$ npm i aes-encryption-unlimited
```

Using yarn:

```bash
$ yarn add aes-encryption-unlimited
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



## License

  [MIT](LICENSE)

---

>  Developed by Karunaaharan Bavaram
