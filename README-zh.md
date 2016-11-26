# Awesome Name [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

### 背景

1. 代码命名有时候是很头疼的事情，又要`语义化`又要`简洁`又要`大众化`，说到底是为了代码的`可维护性`，所以想把之前写代码中经常用到的命名记录下来。

2. 更多是让命名变得更容易，编写代码效率更快，慢慢地喜欢上自己的代码，因为你的代码能告诉别人另外的一种感觉，耐人寻味，把你的代码变成艺术品。比如：

	* `promise`, 之前不知道javascript异步编程的某个基准为啥叫`promise`，
	仔细琢磨了下，感觉意思很耐人寻味。比如javascript异步请求某个数据，它不知道有没有回应，
	promise这个意思就是告诉你我会承诺给你回应的，多么浪漫;
	* `jquery` 的 `on` `off`来监听和销毁事件等简单易用也形象;
	* `fork` github git linux的fork操作，相当于你用餐叉选中你喜欢吃的食物，然后你要怎么吃随便你

### 缩写

1. __截头法__：取单词前几个字母 如 min sec tel
2. __元音剔除法__：只保留辅音字母 如 msg src mgr (辅音字母即是除aeiou之外的字符)
3. __谐音法__：如 4 2 r
4. 参考__HTML标签__、__zepto__ __jquery__库、__linux命令__等命名
5. __其他__: [tj counties](https://github.com/component/countries)：很多国家名的缩写

```javascript
{
	"abbreviation": "abbr", //参考HTML标签命名
	"address": "addr",
	"administrator": "admin",
	"analysis": "anlys",
	"application": "app",
	"application programming interface": "api",
	"are": "r",
	"architecture": "arch",
	"ascending": "asc",
	"attribute": "attr",
	"authentication": "auth",
	"avenue": "ave",
	"background": "bg",
	"body": "bd",
	"business": "biz",
	"button": "btn",
	"buffer": "buf",
	"calculator": "calc",
	"column": "col",
	"command": "cmd",
	"conference": "conf",
	"constant": "const",
	"content": "cnt",
	"context": "cxt",
	"control": "ctrl",
	"copy": "cp",
	"delete": "del",
	"dependency": "dep",
	"develop": "dev",
	"distribution": "dist",
	"division": "div", // HTML标签
	"do it yourself": "diy",
	"document": "doc",
	"down": "dn",
	"download": "dl",
	"element": "el",
	"environment": "env",
	"evaluate": "eval",
	"escape": "esc",
	"execute": "exec",
	"footer": "ft",
	"for": "4",
	"format": "fmt",
	"frequently asked questions": "faqs",
	"function": "fn",
	"header": "hd",
	"identity card": "id",
	"image": "img",
	"information": "info",
	"insert": "ins",
	"introduction": "intro",
	"label": "lbl",
	"library": "lib",
	"list": "ls",
	"lock": "lk",
	"manager": "mgr",
	"markdown": "md",
	"maximum": "max",
	"message": "msg",
	"millimeter": "ml",
	"minimum": "min",
	"module": "mod",
	"move": "mv",
	"multiply": "mul",
	"navigation": "nav",
	"number": "num",
	"option": "opt",
	"package": "pkg",
	"page": "pg",
	"parameter": "param",
	"password": "pwd",
	"picture": "pic",
	"position": "pos",
	"property": "prop",
	"register": "reg",
	"remove": "rm",
	"repository": "repo",
	"request": "req",
	"response": "res",
	"screen": "scr",
	"second": "sec",
	"something": "sth",
	"source": "src",
	"srv": "server",
	"system": "sys",
	"table": "tbl",
	"telephone": "tel",
	"temp": "tmp",
	"template": "tpl",
	"to": "2",
	"user": "usr",
	"value": "val",
	"window": "win"
}
```



### 前缀

```javascript
var prefix = {
	re: '再来一次',
	pre: '之前', // precompile
	post: '之后', // PostCSS
	multi: '很多',
	ex: '前任',
	un: '不', // unobtrusive
	per: '每一个'
}
```

### 后缀

```javascript
var postfix = {
	ed: '过去式', 
	ing: '进行时',
	able: '具备某个能力', // deletable
	es: '名称复数',
	s: '名词复数'
}
```


### 布局

| 语义 | 命名 |
| :--: | :--: |
|布局|layout|
|主体内容|container|
|头部|header|
|主要部分|main|
|侧边栏|sidebar|
|子容器|sub-|
|包含块|-wrap|
|内部的|-inner|
|外部的|-outer|
|行|row|
|列|column|
|区域|region/area/section|
|底部|footer|
|清除浮动|clearfix|
|项|item|


### 模块

| 语义 | 命名 |
| :--: | :--: |
|导航|nav|
|面包屑|crumb|
|菜单|menu|
|选项卡|tab|
|内容|content|
|列表|list|
|排行|rank|
|商标|logo|
|幻灯片|slide|
|提示|tip/msg/hint|
|注册|register|
|弹出框|dialog/model|
|合作伙伴|partner|
|工具条|toolbar|
|标语|banner|
|版权|copyright|
|评论|comment|
|面板|panel|
|手风琴|accordion|
|加载|loading|
|头像|avatar|
|标签|tag|
|表格|table|


### 欢迎补充
毕竟一个人的能力是有限的，希望得到大家的支持，来为代码可维护性做一点努力


### 参考资料
[UI组件规范](http://huixisheng.github.io/fed/docs/ui-coding-style.html)
