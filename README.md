# 如何使用

在完成`./scripts/feeds install -a`操作后执行:
```shell
rm -rf ./feeds/packages/lang/golang
git clone https://github.com/hsldymq/openwrt-golang.git -b v1.25.1 feeds/packages/lang/golang
```