# 简介
为方便在其他项目中使用我自己常用的配置项，省去每个重复配置一遍eslint的规则的繁琐步骤，因此把这些配置规则做成一个npm包，其他项目的lint规则直接继承这个包就有规则了。

# 使用

1. 安装
```bash
npm i @alanlee97/eslint-config -D
```

2. 在当前项目的eslint配置文件中继承`@alanlee97/eslint-config` 
```javascript
module.exports = {
  extends: [
    '@alanlee97/eslint-config', 
    // ...
    ],
  // ...
};

```
