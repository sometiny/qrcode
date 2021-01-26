# qrcode
生成二维码，由jQuery二维码插件改造

# Usage
```
const qrcode = require('jazor-qrcode');
const ins = qrcode(0, 'Q');
console.log(ins.getBase64('hello world!'))
```