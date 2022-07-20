## 合成大西瓜

（gitee好像把图片资源屏蔽了，改到vercel部署了）


魔改版演示地址：https://xiaoxigua.vercel.app/



更新：修改可分数选择代码。修复了结算时分数不正确

用了官方最新的源码，每种小水果已经分开了，不在一张图片里，理论上提高了速度



'葡萄' -> '樱桃' -> '橘子' -> '柠檬' -> '猕猴桃' -> '西红柿' -> '桃' -> '菠萝' -> '椰子' -> '西瓜' -> '大西瓜'

> 添加模式选择和分数选择

# 模式选择

随缘Play：所有水果随机出现，包括大西瓜

圣雄肝帝：刷出的都是小葡萄

原汁原味：原版，随机掉落的是前5种水果。

作弊模式：刷出的都是西红柿

去除小瓜：刷出橘子到菠萝

暴力吃瓜：刷出西瓜

# 分数选择

两倍暴击：原有基础上翻2倍

五倍暴击：原有基础上翻5倍

十倍暴击：原有基础上翻10倍

百倍暴击：原有基础上翻100倍

千倍暴击：原有基础上翻1000倍

万倍暴击：原有基础上翻10000倍

十万伏特：原有基础上翻100000倍

# 分支说明
分支「master」是最新的源码，各种水果图片分开了。魔改了模式选择和分数选择。修复了，结算分数不正常。

分支「mian」是旧的源码，水果图片在一张大图片里。魔改了模式选择和分数选择。

分支「cdnWeb」是使用了jsdelivr加速，演示站gitee上用的就是这个（卡是因为gitee流量小）

分支「default」是最新源码，未改动（结束的全屏广告都有）。

# 怎么修改水果图片

找到\res\raw-assets\下各种水果的路径，替换水果图片，但对图片要求较高

右上角图片\res\raw-assets\8c\

\res\raw-assets\47\

切换两张图片达到字放大缩小



