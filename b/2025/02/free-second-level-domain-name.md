# 获得免费的二级域名

唔，这期咱不讲 [eu.org](https://nic.eu.org/)，不讲 [us.kg](https://nic.us.kg/)，更不讲挂了的 [Freenom](https://www.freenom.com/)，而是：

> [Freedomain.One](https://freedomain.one/)

这个网站提供四种二级域名，一个用户可以**免费**领取 $3$ 个。

这四种分别是：

- `publicvm.com`
- `run.place`
- `linkpc.net`
- `work.gd`

虽然只能免费获得 $3$ 个域名，但是你可以搞许许多多的子域名，所以理论上来说，你可以获得**很多**域名。

## 1 注册/登录

这我就不说了。首页右上角有 `sign up`(注册) 和 `log in`(登录)。

## 2 查询

登录后在首页中间的输入框里输入一个你想要的名字，再选择一种你想要的二级域名。点击 `Check Availability`。

如果是 `Not Available`，试试别的吧。如果是 `Available`，点 `Claim this name`，进入下一个页面。

## 3 得到它

`Registration Term` **选 1 Year**，因为只有这样才是免费的，别怕 $1$ 年不够用，`Expiration Date` 是到期时间，到期时间前 $30$ 天就可以续订，也是免费的，当然，这后面讲。

下面的 IP 地址啥的最开始可以不用管，到了后面还可以改，以及 `Dynamic IP`(动态 IP)依照自己的需求勾选。

我的域名都是用来整 GitHub Pages 的，完全不管 A 记录的 IP 地址，用的都是 CNAME。

## 4 设置 DNS

这就按照自己的需求了。如果用来搞 GitHub Pages(跟我一样)，就添加 CNAME Record(点击 Add Alias),，选 external host，TTL 随你便，Alias 填你要加的子域名，Points to host 填上 `你的GitHub用户名.github.io`，比如我的就填 `cb-x2-jun.github.io`。

## 5 如何续订

登录后到 [https://freedomain.one/Direct.sv?cmd=userDNSList](https://freedomain.one/Direct.sv?cmd=userDNSList)，这里是你的所有域名，Edit DNS 是设置 DNS，这是前面的内容，它右边还有一个 `Manage`，点击这个。

随后你就能看到注册时间(在表格第 $1$ 行)、到期时间(第 $2$ 行)，右边有个 `Renew` 按钮，点击、选 `1 Year`，再点 `Renew Domain` 即可(还没到到期时间前 $30$ 天的时候它不让你免费续订)。

## 6 结语

打字不易，希望各位能到此项目的 **[GitHub 仓库](https://github.com/CB-X2-Jun/CB-X2-Jun.github.io)** 给我一个小小的 Star。
