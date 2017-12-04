下载 nodejs-v10.36.tar.gz 放到lede/openwrt dl 目录
下载 node 包放到lede/openwrt package 目录
make package/node/compile V=s 编译即可
测试于BCM4709/BCM47189/MT7620/MT7628
不支持qca9531/9331 等mipseb机器
mipsel/mipseb有更好选择如node v4/v6
这个包的现实意义仅仅是用于BCM4709/BCM47189这种armv7 nofpu的奇葩soc。
