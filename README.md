# npmdesc
test npm send in here
# test pixiv-login


模拟Pixiv登陆 获取cookie

## Install
```
npm install --save pixiv-login
```

## Usage

``` javascript
const pixivLogin = require('pixiv-login');

pixivLogin({
    username:'your username',
    password:'your password'
}).then((cookie) => {
    console.log(cookie);
}).catch((error) => {
    console.log(error);
});
```
