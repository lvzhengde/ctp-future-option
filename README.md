# ctp-future-option

#### 介绍
基于上期技术CTP平台，C++设计，国内期货期权交易程序。<br>
期权交易品种等参数可配置，自动生成目标期货期权品种的T型报价，根据期权定价模型计算希腊值和隐含波动率。<br>
提供简洁的交易接口，支持中金所、上期所、大商所和郑商所的各种报单类型。<br>


#### 特点

1.  基于Linux操作系统开发，核心代码也可用于Windows操作系统
2.  行情更新和交易策略模块化设计，易于扩展，一种交策略可以同时在多个期权品种上交易，一个期权品种上也可以有多个策略在交易
3.  T型报价根据行情推送实时更新，同时根据期权定价模型完成期权的希腊值和隐含波动率的更新
4.  使用sqlite数据库保存策略参数和交易组合数据
5.  完全使用C/C++语言进行开发，没有混合编程，运行效率高 


#### 使用说明

在使用ctp-future-option之前，读者首先需要确保以下工具已经安装在自己的Linux操作系统上<br>
> gcc/g++/gdb <br>
> cmake <br>
> Qt <br>

使用git clone或者其它方式将ctp-future-option复制到自己Linux本机的工作目录下，在命令行终端，按以下步骤生成可执行文件<br>
> cd  ctp-future-option/solution/build <br>
> cmake . <br>
> make <br>

一切正常的情况下，build目录下将会产生一个名为ctp-future-option的可执行文件。<br>
更为详细的说明请参考doc目录下的文档“CTP期货期权交易程序使用说明.docx”。<br>


#### 免责声明
本设计可以自由使用，作者不索取任何费用。<br>
作者对使用结果不做任何承诺也不承担其产生的任何法律责任。<br>
使用者须知晓并同意上述申明，如不同意则不要使用。<br>

#### 关注开发者公众号
如果需要了解项目最新状态和加入相关技术探讨，请打开微信搜索公众号"时光之箭"或者扫描以下二维码关注开发者公众号。<br>
![image](https://open.weixin.qq.com/qr/code?username=Arrow-of-Time-zd "时光之箭")


