# 汇文明朝体（修正）

**重要：原作者特里王在[知乎](https://zhuanlan.zhihu.com/p/12669052378)上发布了新的汇文系列字体，修复了许多 bug。此仓库大概率不再继续更新。**

原字体在知乎上发布：https://zhuanlan.zhihu.com/p/344103391

但是原字体的一些中文符号，例如 “！”、“？”、“《》” 等，宽度并不是全角字符（占一个汉字宽度），观感较差，如下：

![](images/image.png)

![](images/image2.png)

因此修正了一些常用符号的宽度，使之符合中文全角字符宽度，符号作居中处理。

修正效果如下：

![](images/image3.png)

![](images/image4.png)

目前已经修正的符号如下：

| 符号 |       名称       | unicode 编号 |
| :--: | :--------------: | :----------: |
|  《  |    左双书名号    |     300A     |
|  》  |    右双书名号    |     330B     |
|  「  |   中式单开引号   |     300C     |
|  」  |   中式单关引号   |     300D     |
|  『  |   中式双开引号   |     300E     |
|  』  |   中式双关引号   |     300F     |
|  【  |     左方括号     |     3010     |
|  】  |     右方括号     |     3011     |
|  ︗  | 左直排空心方括号 |     FE17     |
|  ︘  | 右直排空心方括号 |     FE18     |
|  ︵  |    左直排括号    |     FE35     |
|  ︶  |    右直排括号    |     FE36     |
|  ︷  |   左直排花括号   |     FE37     |
|  ︸  |   右直排花括号   |     FE38     |
|  ︹  |  左直排六角括号  |     FE39     |
|  ︺  |  右直排六角括号  |     FE3A     |
|  ︻  |   左直排方括号   |     FE3B     |
|  ︼  |   右直排方括号   |     FE3C     |
|  ︽  |  左直排双书名号  |     FE3D     |
|  ︾  |  右直排双书名号  |     FE3E     |
|  ︿  |  左直排单书名号  |     FE3F     |
|  ﹀  |  右直排单书名号  |     FE40     |
|  ﹁  | 中式直排单开引号 |     FE41     |
|  ﹂  | 中式直排单关引号 |     FE42     |
|  ﹃  | 中式直排双开引号 |     FE43     |
|  ﹄  | 中式直排双关引号 |     FE44     |
|  ！  |      感叹号      |     FF01     |
|  （  |      左括号      |     FF08     |
|  ）  |      右括号      |     FF09     |
|  ：  |       冒号       |     FF1A     |
|  ；  |       分号       |     FF1B     |
|  ？  |       问号       |     FF1F     |

更多的格式请在 [release](https://github.com/bosswnx/huiwenmincho-improved/releases) 下载。

TODO:

- [ ] 修正一些符号的位置（例如「」）
- [ ] 动态宽度

也欢迎各位参与贡献~ :) 

