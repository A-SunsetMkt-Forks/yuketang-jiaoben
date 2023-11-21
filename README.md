# 雨课堂刷课助手

### 脚本使用：

在通知栏点击开始刷课即可。

### 已适配雨课堂学校及网址：

学校：中原工学院，河南大学研究院，广东财经大学，辽宁大学，河北大学，中南大学，电子科技大学，华北电力大学，上海理工大学研究生院及其他院校... 

网址：changjiang.yuketang.cn，yuketang.cn ...

### 注意事项：

本脚本主要是通过location.back()返回课程页面的，所有请不要在刷课课程中跳转页面，否则脚本就会中断，如果不慎跳转，刷新重启脚本即可。

### 脚本来历：

油猴上有好多刷课脚本，不过我试了好几个点赞量很多的脚本却均在雨课堂上并不生效，很佩服这些大佬写上千行代码实现各平台的刷课脚本，也被吓到过，不过自己最终还是实现了雨课堂专用脚本，脚本内容简洁详细，仅100余行，且有一定的代码备注，想学习的同学可以容易查阅。不过，写脚本倒是锻炼自己dom,bom的好机会。学习了很多。

欢迎大家补充：[github地址](https://github.com/Niuwh/yuketang-jiaoben)

### 温馨提示：

好好学习，天天向上，适当刷课，快乐成长^_^

### 贡献者名单：

+ duck123ducker     解决了雨课堂进入后台意外暂停的bug
+ insorker          增加错误页面匹配提醒 && 修改倍速函数，支持3倍速

### 赞助者名单：

+ 晚睡早起 资金赞助
+ 余生
+ 心向璀璨 资金赞助
+ LZ 资金赞助
+ 陌黎 资金赞助
+ ycj 资金赞助
+ 对赞助的朋友表示感谢，你们给予我的鼓励是我前进的动力！

---

如有任何问题或提议，欢迎大家访问我的网站：[http://niuwh.cn](http://niuwh.cn) ,里面有我的联系方式。或者脚本下@我。

### 更新记录：

+ 1.0.0 大更新，改善了界面效果，开始逐渐融合各种雨课堂版本。代码量提升至500余行。
+ 2.1.0 小更新，之前版本号从0.0.1开始算，觉得不妥，现在改为1.0.5 -> 2.1.0.新增一条刷课线路。
+ 2023.10.1 代码托管到github,欢迎各位开发者提出 pull request.为脚本填一份力量。
+ 解决了雨课堂进入后台意外暂停,更改rate为1后,仍然二倍速,进入批量意外卡顿的bug
+ 修复了课程已经刷完，直接检测导致observer为undefined的问题，舍弃了playOut()的判断方法
+ 2023.11.10 2.1.6 修复网站更新出现bug
+ 2023.11.17 2.2.0 增加错误页面匹配提醒 && 修改倍速函数，支持3倍速
+ 2023.11.21 2.2.1 匹配所有可刷的雨课堂网址，增加倍速显示