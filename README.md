tripPlan
========

This is alse a test of jekyll on github.

This time ,try google-bootstrap.

----

#背景

最近正在规划一个去日本旅游的行程，为了能井井有条的规划好大约15天的行程，决定找一个工具，至少是类似的玩意儿来辅助一下，能快速生成一个清晰有条理，又美观的行程单。

可是事与愿违，在经过半天的搜索后，终于放弃了。灵机一动，想起来可以自己用Jekyll拼一个出来，放在Github上，也不枉自己作为一个攻城师了。

说干就干。

#说明

我做的这个行程单，主要是有三部分组成。
 + **index**：首页。用于展示一个行程单List。
 + **trip**: 一次旅行的行程单。需要填写以下内容
  - **topic**：主题，用主题来区分不同的行程；内容是综述。
  - **category**: 填“trip”。用于由index聚合
  - content: 旅行的综述
 + **post**: 具体每一天的行程。目前没有做细分。需要注意以下的属性。
  - **category**： 等于trip的topic。用于聚合一次旅行的post
  - **date**：目前是按date的顺序来排的。
  - content: 具体当天的安排

#例子
[点我][1]


[1]:[http://wellwy.github.io/tripplan/](http://wellwy.github.io/tripplan/)