### 背景
代码命名有时候是很头疼的事情，又要`语义化`又要`简洁`又要`大众化`，
说到底就是为了代码的`可维护性`，所以想把之前写代码中经常用到的命名记录下来。
更多是让命名容易

### 简写

> 有利于代码的简洁

```javascript
/**
 * 命名规则
 * 1. 截头法：取单词前几个字母 如 min sec tel
 * 2. 元音剔除法：只保留辅音字母 如 msg src mgr (辅音字母即是除aeiou之外的字符)
 * 3. 谐音法：如 4 2 r
 */
{
	"biz": "business",
	"ave": "avenue",
	"id": "identity card",
	"min": "minute",
	"min": "minimum",
	"max": "maximum",
	"ml": "millimeter",
	"no": "number",
	"num": "number",
	"sec": "second",
	"tel": "telephone",
	"bg": "background",
	"ctrl": "control",
	"doc": "document",
	"esc": "escape",
	"info": "information",
	"img": "image",
	"lib": "library",
	"mgr": "manager",
	"msg": "message",
	"pwd": "password",
	"pic": "picture",
	"pos": "position",
	"src": "source",
	"param": "parameter",
	"sys": "system",
	"admin": "administrator",
	"btn": "button",
	"addr": "address",
	"4": "for",
	"2": "to",
	"analysis": "anlys", // 自定义
	"diy": "do it yourself",
	"r": "are",
	"rm": "remove",
	"mv": "move",
	"server": "srv",
	"usr": "user",
	"tmp": "temp",
	"win": "window",
	"bd": "body",
	"hd": "header",
	"nav": "navigation",
	"faqs": "frequently asked questions",
	"ft": "footer",
	"col": "column",
	"lbl": "label", // 自定义
	"reg": "register",
	"dl": "download", // 自定义
	"cnt": "content",
	"cp": "copy",
	"lk": "lock", // 参看windows键盘
	"scr": "screen", // 参看windows键盘
	"del": "delete", // 参看windows键盘
	"ins": "insert", // 参看windows键盘
	"dn": "down", // 参看windows键盘
	"pg": "page",
	"conf": "configuration",
	"env": "environment",
	"exec": "execute",
	"dist": "distribution",
	"ls": "list", // linux
	"app": "application",
	"res": "response",
	"req": "request"
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
|行|row|
|列|column|
|区域|region/area/section|
|底部|footer|


### 模块名

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
|弹出框|dialog|
|合作伙伴|partner|
|工具条|toolbar|
|标语|banner|
|版权|copyright|
|评论|comment|
|面板|panel|



### 欢迎补充
毕竟一个人的能力是有限的，希望得到大家的支持，来为代码可维护性做一点努力


### 参考资料
[UI组件规范](http://huixisheng.github.io/fed/docs/ui-coding-style.html)
