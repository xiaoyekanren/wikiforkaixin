1. 给npm设置国内源
```shell
# 该步骤执行完之后，会将源的信息写到 /Users/$(whoami)/.npmrc 下
npm config set registry https://registry.npmmirror.com
```

2. 将国内源重置为默认源
``` shell
npm config delete registry
```

3. 查看当前npm源
```shell
npm config get registry
```