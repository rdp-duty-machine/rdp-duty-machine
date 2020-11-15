### 这是什么？

这是一个借助Github搭建的备份网络文章的服务。由于Github对墙内软件业非常重要，不会轻易被墙。所以对于容易被和谐的墙内平台文章，以及已经被屏蔽的墙外平台文章，都可以借助Github让他们在墙内能访问到。

通过本项目，你可以在线匿名地为一篇网络文章创建一个抗和谐的版本。

### 目前支持什么网站？

当前支持的网站有：微信公众平台，微博文章，知乎专栏，豆瓣日记，豆瓣小组话题，matters，telegraph，chinadigitaltimes，rfa。

### 如何提交要抓取的页面？

我们提供了一个匿名的在线提交入口：https://rdp-duty-machine-form.vercel.app/ 。将网址粘贴到表单里点击提交，等待一分钟左右，机器人会把文章内容跟贴到当前网址里。

同时你可以查看[所有已提交的文章抓取](https://github.com/rdp-duty-machine/rdp-duty-machine/issues?q=is%3Aclosed+is%3Aopen)，还有[已抓取成功的文章列表](https://github.com/rdp-duty-machine/rdp-duty-machine/issues?q=label%3Afetched+is%3Aclosed)。

### 使用本服务有哪些风险？

我们的提交入口是开源的，并且正在运行的源码可以接受监督，详见[rdp-duty-machine-form项目](https://github.com/rdp-duty-machine/rdp-duty-machine-form)，我们没有保存和泄露你的ip和提交信息。

但是你的身份仍有可能泄露，理论上中国有能力监视墙内对提交入口域名的访问，如果他们知道你访问了这个域名，又在同时看到了新建的抓取请求，你的身份有可能就会被和抓取内容联系起来。尽管这样的风险不大，我们建议尽量开启vpn等代理访问提交入口和提交，以保证最大的匿名性。

### 对端点星的声援

这个项目是受[端点星计划](https://github.com/Terminus2049/Terminus2049.github.io)的启发而作，为的是可以在不登录github的情况下也可以备份网络文章，满足普通用户的备份需求。

而恰好在本项目刚刚诞生之际，得知了端点星计划志愿者陈玫、蔡伟及其女友小唐被当局关押的消息，使我觉得我有义务为他们呼唤关注。[陈玫、蔡伟被秘密关押54天后被以寻衅滋事罪逮捕](https://github.com/rdp-duty-machine/rdp-duty-machine/issues/5)。

我们依照《中华人民共和国宪法》第三十五条：“中华人民共和国公民有言论、出版、集会、结社、游行、示威的自由。”，敦促当局立即停止违反宪法，侵犯公民自由的行为。

### 其他

本项目使用[rdp-duty-machine-action](https://github.com/rdp-duty-machine/rdp-duty-machine-action)搭建，你可以使用它搭建自己的版本。

在转载github.com的链接时，可以使用 https://git.io/ 短链接服务，以增加审查的难度。

### 友情链接

公益社会类项目汇总： https://github.com/NodeBE4/impact/

武汉疫情报道备份项目：https://github.com/lestweforget/wuhan2019

以时间线的形式展示新冠肺炎疫情、香港反送中等社会议题：https://github.com/chinatimeline/chinatimeline.github.io

