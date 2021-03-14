## babel-plugin-oxygen

一个简单的将程序中`==`转换成`===`的`babel` plugin，已发布到`npm`

## 使用

### 安装

```bash
yarn add @babel/core @babel/cli babel-plugin-oxygen
```

### 配置

```javascript
module.exports = function (api) {
  api.cache(true);

  return {
    plugins: ['oxygen'],
  };
};
```
