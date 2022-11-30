# 跟老齐学Python：Django实战

![](https://public-tuchuang.oss-cn-hangzhou.aliyuncs.com/Django2%E7%AB%8B%E4%BD%93%E5%9B%BE_20200117164816.png)

## 说明

- 《跟老齐学Python：Django实战（第2版）》是针对Django2.x
- 《跟老齐学Python：Django实战》，即第1版，是针对Django1.x

请根据版本进行选择。

## 简介

本书是以Python为基础进行web应用开发的进阶读物。书中以一个实例项目为主线，使用Django2开发框架，在实践中边学边做，理论联系实际。每节都配有思维导图，使读者对项目需求一目了然；每章都有知识点和文档导读，引导读者“知其所以然”。相信认真阅读本书的读者，不仅能够得到“鱼”， 更能得到“渔”，从而具备独立开发项目的能力。

本书适合已经具有Python基础技能、进行Web应用开发的读者阅读。

## 购买

- 各大电商平台有售
- 电子工业出版社天猫旗舰店

## 在线资源

### 源码

源码仓库：[https://github.com/qiwsir/DjangoPracticeProject](https://github.com/qiwsir/DjangoPracticeProject)

**注意：**源码仓库中针对两个版次，第一版对应的是`mysite`目录，第二版对应的是`mysite_2`目录。

### 辅助文章

在我的微信公众号【老齐教室】和[博客](https://qiwsir.github.io)上发布了很多关于web开发的文章，供参考。

请阅读：[WEB开发文章汇总](https://mp.weixin.qq.com/s/AiltlCOjpFP1U13mKvzCAg)

## 勘误与修订

### 版次：2019年1月第2版

**印次：2019年1月第1次印刷**

1. 第65页面

   - 位置：正文，第2自然段
   - 原文：如果要将表单中的数据写入数据库表或者修改某些~~记录~~的值，
   - 修订：如果要将表单中的数据写入数据库表或者修改某些字段的值，
   - 说明：将原文中的“记录”修改为“字段”。

2. 第79页面

   - 位置：代码，第2段

   - 原文：`\{\% block title \%\}passowrd change\{\% endblock \%\}\{\% block content\%\}` ….（直到80页本段代码段结束）

   - 修订：

     ![](https://gitee.com/qiwsir/images/raw/master/2021-2-15/1613369137287-dc.png)

     - 说明：原文对password_reset_form.html代码有误，修改为如上所示代码。因为排版问题，上述显示可能有误，请参考：[https://github.com/qiwsir/DjangoPracticeProject/blob/master/mysite_2/templates/account/password_reset_form.html](https://github.com/qiwsir/DjangoPracticeProject/blob/master/mysite_2/templates/account/password_reset_form.html)

   ### 版次： 2017年10月第1版

   **印次：2017年10月第7次印刷**

   1. 页码：144页，
      - 代码段，第2段
      - 原文：`\{\% extends "ArticleManage/base.html" \%\}`
      - 修改为：`\{\% extends "article/base.html" \%\}`

   **印次：2017年10月第2次印刷**

   1. 14页
      - 正文，正数第一行
      - 原文：…并且以参数max_length=30的形式…
      - 修改为：…并且以参数max_length=300的形式…
   2. 39页
      - 代码段倒数第一段，倒数第三行
      - 原文：`\{\% block javascritp \%\}`
      - 修改为：`\{\% block javascript \%\}`

   3. 71页
      - 正文，倒数第一行
      - 原文：FieldField：表示该字段…
      - 修改为：FileField：表示该字段…

   **印次：2017年10月第1次印刷**

   1. 26页
      - 代码段第二段，注释⑦和⑨、⑩的href和src地址。
      - 原文：

   ```html
   … href="http://libs.baidu.com/bootstrap/3.0.3/css/bootstrap.min.css">   …     #⑦
   
   … src="http://libs.baidu.com/jquery/2.0.0/jquery.min.js"> …      #⑨
   
   … src="http://libs.baidu.com/bootstrap/3.0.3/js/bootstrap.min.js"> …    #⑩
   ```

      - 修改为：

   ```html
   … href="https://cdn.bootcss.com/bootstrap/3.3.7/css/bootstrap.min.css">   …     #⑦
   
   … src="https://cdn.bootcss.com/jquery/3.2.1/jquery.js"> …      #⑨
   
   … src="https://cdn.bootcss.com/bootstrap/3.3.7/js/bootstrap.min.js"> …    #⑩
   ```

   2. 128页
      - 代码段，第二段，第三行。
      - 原文：`>>> user = User.object.get(id=11)`
      - 修改为：`>>> user = User.objects.get(id=11)`

   3. 181页
      - 正文倒数第一段
      - 原文：然后对read_article()函数进行重写，
      - 修改为：然后对article_detail()函数进行重写，

   4. 181页
      - 代码段倒数第一段
      - 原文：`def read_article(request, id, slug):`
      - 修改为：`def article_detail(request, id, slug):`
