# shuabu
基于zepp life的微信,QQ,支付宝每天自动刷步，支持多账户,支持青龙和actions定时执行,再也不需要怕忘记了
## 各位既然用了那就随手点个Satr行不行
## 使用方式
`ql repo https://ghproxy.com/https://github.com/wdvipa/shuabu/raw/main/shuabu.py`
如需直接运行或不用环境变量吧文件开头的cs变量改为2即可
### 青龙订阅
青龙最新版本订阅请填写下面内容（没写的别乱填）
|数据|内容|
|----|----|
|名称|自动刷步|
|链接|`https://kkgithub.com/wdvipa/shuabu.git`|
|定时类型|crontab|
|定时规则|	2 2 28 * *|
|白名单|ssp.py|
## 手机号不能注册可以去用找回密码注册,如果一定要邮箱改login的链接self.user变量前的+86去掉即可
## 想要把所有推送改一成一个变量的改下头部代码即可
## 青龙变量
| 参数 | 说明                     |  格式  |
| ---- | -----------------------  |  -------  |
| shuabu  | 账号\|密码 |  账号\|密码\|步数区间  多账号用回车隔开  |
| shuabu_fs  | 推送的平台 |  多个平台使用&隔开 支持push,kt  |
| shuabu_push  | Pushplus的推送token |  token  |
| shuabu_ktkey  | 酷推的key |  key  |
| 暂不支持  | 暂不支持 |  暂不支持  |
