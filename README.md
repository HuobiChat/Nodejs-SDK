# HuobiChat Open Platform Node.js SDK

HuobiChat开发平台Node.js SDK

## Install

```
npm install --save hcopen-sdk
```
## Usage
```javascript
const sdk = require('hcopen-sdk')

new sdk({
    appUid: '111',
    appSecret: '222',
}).getUserInfo(code).then(data) => {
    console.log(data);
}).catch((error) =>{
    console.log("sdk failed");
})
```


