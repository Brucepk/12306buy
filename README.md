# 用Python抢火车票加邮件通知


## 本代码文章首发于公众号「Python知识圈」，如需转载，请通过公众号联系作者pk哥，谢谢

![公众号](https://github.com/Brucepk/pk.github.io/blob/master/gzh.jpg)

目录
抢票效果

splinter 库安装导入

准备工作：初始化属性

登录功能实现

邮件通知实现

查票功能实现

买票功能实现

源码获取方式

抢票效果
运行代码后，Splinter 会自动启动浏览器，代替手工去操作页面，执行打印日志如下。

请输入验证码...
开始购票...
第1次点击查询...
第2次点击查询...
第3次点击查询...
第4次点击查询...
第5次点击查询...
第6次点击查询...
第7次点击查询...
第8次点击查询...

预订失败...
开始预订...
开始选择用户...
提交订单...
确认选座...
预订成功...
抢票通知邮件发送成功！
抢票成功后，我们会收到抢票成功的邮件。