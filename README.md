#### 自动驾驶的安全方面
---

* 彭杰
  * 风险：小车未来工作在网络环境中，系统中有云端的组成部分，有攻击隐患
    * 目前代码中为对这些进行考虑
    * 网络通信更容易被攻击
* 吉建民老师
    * 实验级别和普通机器人级别
      * 无论4G，wifi，通信，只要伪装成结点发消息，或者不发消息让网络阻塞，只要有权限进入系统，随便干什么，系统都会出问题，目前没有考虑安全方面
      * 不是实时系统，一有延迟就会出问题。
    * 实车和商业级别
    * 很多车厂can协议不公开，一旦公开极易被攻击，只要插上蓝牙和4G，就能远程控制车。can协议毫无安全性可言，通过蓝牙，无线将伪装信息发过去，刹车油门都会出问题。
        * mobileeye和特斯拉，mobileeye远程连接网络，将感知的数据传到自己的云上，云上也能更新车上硬件，伪装mobileye更新数据，发送伪装的消息，直接挂掉
        * 特斯拉 通过OTA实时在线偷偷更新系统和上传数据，会偷偷更新bug，用户没有权限停止，不开源.特斯拉的所有车都连在那个系统，一旦出错，所有车都可能出问题。
* 张燕咏老师
	* 有学生做过相关的工作，可以进一步咨询

#### 可视化方面
* 张燕咏老师
    * 可以看一些在可视化方面专业的做法，在可视化的专业的层面做一些贡献，将想法放在方法论上
    * 考虑一下从科研，从技术方面比较正规的方法论，不仅要有工具还要有一些说道。要有方法论就更好一点

* 在复杂软件工程分析-软件工程类的方向进行调研,多语言编写的module的依赖的分析等 袁晓如 陈宝权
* 静态分析，工具理解可视化

| 会议  | CCF  | CORE | 链接|
| :------------ |:---------------:| :-----:| :-----:|
|   CHI    |   A     |    A+    |  https://dblp.uni-trier.de/db/conf/chi/    |
|   VAST    |        |        |    https://dblp.uni-trier.de/db/conf/ieeevast/     |
|  InfoVis     |        |   A+     |   https://dblp.uni-trier.de/db/conf/infovis/     |
|  PacificVis      |    C    |        |  https://dblp.uni-trier.de/db/conf/apvis/      |
|  ChinaVis     |        |        |   http://www.chinavis.org/2020/     |
|  VizSEC      |        |        |    https://dblp.uni-trier.de/db/conf/vizsec/    |
|  SciVis     |        |        |    https://dblp.uni-trier.de/db/conf/scivis/    |
|    GD   |        |     A   |     https://dblp.uni-trier.de/db/conf/gd/   |
|    IEEE VIS    |     A   |   A     |   https://dblp.uni-trier.de/db/conf/visualization/index.html     |
|EuroVis  |B |    | https://dblp.uni-trier.de/db/conf/vissym/|


| 期刊  | CCF   | 链接|
| :------------ |:---------------:| :-----:|
|   TVCG    |   A            |    https://dblp.uni-trier.de/db/journals/tvcg/  |
|    TIST   |               |    https://dblp.uni-trier.de/db/journals/tist/     |
|   journal of visual languages and computing  |               |    https://dblp.uni-trier.de/db/journals/vlc/    |
|   Journal of Visualization |           |     https://dblp.uni-trier.de/db/journals/jvis/   |
|  Journal of Software  |    |     |  https://dblp.uni-trier.de/db/journals/jsw/  |
