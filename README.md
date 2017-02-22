# npm-publish-demo

npm-publish-demo-xiao

#注意事项

1、记得将npm下载源地址改为官方的

```
npm config set registry http://registry.npmjs.org
```
2、生产package.json文件，里面要注意参数，repository:""一定要填写仓库地址，因为最后npmjs，会从线上仓库获取。

3、如果你以后修改了代码，然后想要同步到 npm 上的话请修改 package.json 中的 version 然后再次 publish，更新的版本上传的版本要大于上次

4、别忘了填写正确的package.json的main路径文件

# 参考链接

http://www.cnblogs.com/pingfan1990/p/4824658.html

https://webpack.js.org/guides/author-libraries/