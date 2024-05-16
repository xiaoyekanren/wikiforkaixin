1. npm设置源
```shell
# 给npm设置国内源
# 该步骤执行完之后，会将源的信息写到 /Users/$(whoami)/.npmrc 下
npm config set registry https://registry.npmmirror.com

# 将国内源重置为默认源
npm config delete registry

# 查看当前npm源
npm config get registry
```


2. electron安装不上

```shell
# 切换electron的源为国内即可，以后下载electron 都会走这个地址
echo "ELECTRON_MIRROR=\"https://npmmirror.com/mirrors/electron/\"" >> ~/.zshrc
```
