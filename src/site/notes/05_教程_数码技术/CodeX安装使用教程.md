---
{"dg-publish":true,"permalink":"/05_教程_数码技术/CodeX安装使用教程/","tags":["gardenEntry"]}
---

By wanye

## CodeX 简介
Codex 是 OpenAI 推出的 **AI 编码助手 / 编码智能体**，主要用来帮助开发者完成软件开发相关工作。
**主要功能**
1. **写代码**：你用自然语言描述需求，Codex 可以生成代码，并尽量适应现有项目结构和编码风格。
2. **理解代码库**：可以阅读和解释陌生或历史项目，帮助你快速看懂模块、逻辑和系统组织方式。
3. **并行处理任务**：官方介绍里强调它支持多个智能体并行处理不同编码任务

得益于现在 OpenAI 官方对于免费用户和团队空间的使用配额的宽松，我们可以使用 Codex 帮我们完成一系列的代码，文件整理，项目管理等工作。尤其推荐月抛的 business 方案，可以在咸鱼上找到10元以内一个月的计划。 

![Pasted image 20260319194425.png\|556](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319194425.png)

使用 Codex 需要以下三个条件
## 1 . 魔法环境
因人而异，我推荐使用 clash+订阅的方式进行外网访问，由于 clash 官网开发者删库跑路，目前可以采用第三方维护的 FlClash 作为翻墙工具，辅助购买节点订阅。

1. 第一步进入Flclash github网址，进入 release下载对应设备的安装包
![Pasted image 20260319194406.png\|508](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319194406.png)
![Pasted image 20260319194248.png\|489](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319194248.png)
如果无法访问 github 也可以下载附带的网盘链接中的安装包

2. 下载安装，进入xfld节点订阅1网址进行账户申请和订阅购买，邮箱可以任意填写，不会使用邮箱验证，记住账户密码。(备用的魔戒也是类似的购买方法)
![Pasted image 20260319194534.png\|472](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319194534.png)
进入商店后进行订阅购买，由于使用 AI 工具对于流量使用并不大，所以推荐购买一次性的套餐，如果购买周期性务必购买**月付!！** 
![Pasted image 20260319194729.png\|461](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319194729.png)

购买套餐后在仪表盘页面出现订阅信息，点击导入订阅，复制订阅地址到 Flclash 中，后续不同设备端的教程在网站的教程页面进行了详细讲解，具体内容可看网站教程页
![Pasted image 20260319195205.png\|517](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319195205.png)

节点订阅：
[xfld节点订阅1](https://my.xfltd.org/#/stage/dashboard)
[魔戒订阅](https://www.mojie.me/#/plan/2)

翻墙工具：
[Flclash github网址](https://github.com/chen08209/FlClash)
[云盘 flclash 链接](https://share.fnnas.net/s/193434a61d574861be)
## 2 . Chatgpt 账户
 chatgpt 访问时需要使用魔法环境
现在 chatgpt 支持谷歌，微软，苹果和邮箱登录，鉴于谷歌账户对于国区手机号不支持，所以采用邮箱注册或者微软账户登录的方式, 注册的年龄大于18岁，注意邮件的验证的网络环境。
![Pasted image 20260319203241.png\|284](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319203241.png)


[chatgpt 账户申请教程](https://zhuanlan.zhihu.com/p/1961450443373810229?utm_source=chatgpt.com)
### Bussiness 工作空间套餐购买
记住注册 chatgpt 账户的邮箱，去咸鱼搜索 team 或 Bussiness（chatgpt 是违禁词没有检索结果）。选一个价格合适，商家信用为优秀以上。注意都是月抛的team，订阅期到期后无法进入工作空间，而且有可能后续 openAI 封禁工作空间，导致聊天记录丢失，所以注意保存记录。且用且珍惜
![7d07631379c39e0763038882b2a121c.jpg\|408](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/7d07631379c39e0763038882b2a121c.jpg)

将自己的邮箱发过去给商家，会被拉入工作空间，chatgpt 聊天界面选择与个人的聊天记录是隔离的，可以在界面的右下角切换至工作空间，这个只会影响网页版的chatgpt的聊天记录，Codex的项目不会随工作空间的封禁而导致丢置。
![Pasted image 20260319204353.png](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319204353.png)
## 3 . Window Codex 软件  

Window 版本的 Codex需要在微软商店进行下载，注意此时如果是国区的微软账户不要挂梯子，使用国内网络正常下载。下载完成后挂上梯子，在windows开始页面点击打开 codeX（如果不挂梯子会无法访问）

![Pasted image 20260319213656.png](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319213656.png)

然后进入 Codex使用chatgpt进行登录，此处登录选择工作空间登录才有更多的使用额度
![Pasted image 20260319214430.png\|474](/img/user/05_%E6%95%99%E7%A8%8B_%E6%95%B0%E7%A0%81%E6%8A%80%E6%9C%AF/attach/Pasted%20image%2020260319214430.png)

[ 安装教程](https://www.bilibili.com/video/BV174Pyz7ENV/?spm_id_from=333.337.search-card.all.click&vd_source=b7a861a59669f93c5712c3f1de030219)

