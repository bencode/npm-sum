# npm-sum
发布npm包测试


我希望使用者可以这样使用

```js
const sum = require('npm-sum-test');

sum(1, 2, 3, 4, 5);
```


需要弄清楚以下点：

- 上面require('npm-sum-test')，它实际上加载的是什么文件？ 可以配置吗？
- version的三个数字分别代表什么，版本策略是怎么样的？
