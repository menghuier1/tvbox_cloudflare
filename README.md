# 项目说明
---

项目主要是利用Cloudflare Workers 和 Pages部署tvbox api在线接口源(json),其他的视频在线源是json格式也可以
项目期望：已存在在github上的项目，更新其index.js文件(tvbox api在线接口源),并自动出发自动触发Cloudflare Workers 和 Pages中对应项目自动更新,避免在线源数据过时，
 1. index.js文件(tvbox api在线接口源)托管在github上可随时更新
 2. index.js文件(tvbox api在线接口源)程序部署在Cloudflare Workers 和 Pages上，
 3. 在Cloudflare Workers 和 Pages上配置自定义域名即可访问
 4. index.js文件(tvbox api在线接口源)默认使用饭太硬的源
 5. tvbox api在线接口源项目：https://github.com/qist/tvbox
 6. 其他源
```shell
接口收集于网络，仅供测试交流，禁止售卖非法使用！

不定期删改内容，如有冒犯，请联系删除。

本帖短链接：http://z.qiqiv.cn/123

单仓是多条线路，多仓是多条单仓；

蜂蜜，OK版仅支持加载单仓，无法加载多仓；

俊于版和taka版不支持仓库链接，只能使用下方的线路！

如果解析配置失败，下载最新版再试试！

>>>TVBox（影视仓）最新版下载

★饭太硬
http://www.饭太硬.net/tv

★饭太硬（备用）
http://www.饭太硬.art/tv

★饭太硬（备用）
http://fty.xxooo.cf/tv

★饭太硬（备用）
http://fty.888484.xyz/tv

★饭太硬（备用）
http://fty.333232.xyz/tv

★小米
https://gh-proxy.org/https://raw.githubusercontent.com/ggrrttyyiii/CatVodSpider/refs/heads/main/json/demo.json

★肥猫
http://feimao.pro

★王二小
https://9280.kstore.vip/newwex.json

★摸鱼儿
http://我不是.摸鱼儿.top

★潇洒
https://9877.kstore.space/AnotherD/api.json

★小虎斑
http://hb.小虎斑.site:25252/仅供测试

★南风
https://gh-proxy.com/https://raw.githubusercontent.com/yoursmile66/TVBox/refs/heads/main/XC.json

★香雅情
https://gh-proxy.com/https://raw.githubusercontent.com/xyq254245/xyqonlinerule/main/XYQTVBox.json

★少儿频道
https://jihulab.com/ymz1231/xymz/-/raw/main/ymshaoer
```
---

# 使用cloudflare初始化项目

```power

$ npm create cloudflare@latest -- tvboxapi

> npx
> create-cloudflare tvboxapi


──────────────────────────────────────────────────────────────────────────────────────────────────────────
👋 Welcome to create-cloudflare v2.70.15!
🧡 Let's get started.
📊 Cloudflare collects telemetry about your usage of Create-Cloudflare.

Learn more at: https://github.com/cloudflare/workers-sdk/blob/main/packages/create-cloudflare/telemetry.md
──────────────────────────────────────────────────────────────────────────────────────────────────────────

╭ Create an application with Cloudflare Step 1 of 3
│
├ In which directory do you want to create your application?
│ dir ./tvboxapi
│
├ What would you like to start with?
│ category Hello World example
│
├ Which template would you like to use?
│ type Worker only
│
├ Which language do you want to use?
│ lang JavaScript
│
├ Copying template files
│ files copied to project directory
│
├ Updating name in `package.json`
│ updated `package.json`
│
├ Installing dependencies
│ installed via `npm install`
│
├ Do you want to add an AGENTS.md file to help AI coding tools understand Cloudflare APIs?
│ no agents
│
╰ Application created

╭ Configuring your application for Cloudflare Step 2 of 3
│
├ Installing wrangler A command line tool for building Cloudflare Workers
│ installed via `npm install wrangler --save-dev`
│
├ Retrieving current workerd compatibility date
│ compatibility date 2026-07-29
│
├ Do you want to use git for version control?
│ yes git
│
├ Initializing git repo
│ initialized git
│
[master (root-commit) 22d7d36] Initial commit (by create-cloudflare CLI)
 10 files changed, 4181 insertions(+)
 create mode 100644 .editorconfig
 create mode 100644 .gitignore
 create mode 100644 .prettierrc
 create mode 100644 .vscode/settings.json
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 src/index.js
 create mode 100644 test/index.spec.js
 create mode 100644 vitest.config.js
 create mode 100644 wrangler.jsonc
├ git commit
│
╰ Application configured

╭ Deploy with Cloudflare Step 3 of 3
│
├ Do you want to deploy your application?
│ no deploy via `npm run deploy`
│
╰ Done

────────────────────────────────────────────────────────────
🎉  SUCCESS  Application created successfully!

💻 Continue Developing
Change directories: cd tvboxapi
Deploy: npm run deploy

📖 Explore Documentation
https://developers.cloudflare.com/workers

🐛 Report an Issue
https://github.com/cloudflare/workers-sdk/issues/new/choose

💬 Join our Community
https://discord.cloudflare.com
────────────────────────────────────────────────────────────
```

# (可选)使用wrangler部署
---

> #创建项目
>
> npm create cloudflare@latest -- tvboxapi
>
> ```power
> create-cloudflare@2.70.15
> Ok to proceed? (y) y
> 
> ├ What would you like to start with?
> │ category Hello World example #创建示例模板
> │
> ├ Which template would you like to use?
> │ type Worker only #使用worker
> │
> ├ Which language do you want to use?
> │ lang JavaScript #使用json
>  Do you want to add an AGENTS.md file to help AI coding tools understand Cloudflare APIs?
> │ no agents #不创建AGENTS.md文档
> ├ Do you want to use git for version control?
> │ no git #不适用git初始化
> ├ Do you want to deploy your application?
> │ no deploy via `npm run deploy` #不部署程序
> ```
>
> #登录
>
> npx wrangler login
>
> #本地验证
>
> npx wrangler dev
>
> #部署
>
> npx wrangler deloy



# 配置index.js

> tvboxapi\src\index.js

```json
/**
 * Welcome to Cloudflare Workers! This is your first worker.
 *
 * - Run `npm run dev` in your terminal to start a development server
 * - Open a browser tab at http://localhost:8787/ to see your worker in action
 * - Run `npm run deploy` to publish your worker
 *
 * Learn more at https://developers.cloudflare.com/workers/
 */

export default {
  async fetch(request, env, ctx) {
    // 假设这是你的 JSON 数据
    const tvboxFtyAPIJsonData =
{
"spider":"./jar/fan.txt;md5;8432d174d72d5b608ae1bcd16d966847",
"logo":"https://avatars.githubusercontent.com/u/58679624?v=4",
"lives":[{"name":"初秋语•ipv4","type":0,"url":"./list.txt","playerType":2,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo": "https://live.fanmingming.com/tv/{name}.png"},
{"name":"YanG•综合","type":0,"url":"https://tv.iill.top/m3u/Gather","ua": "okhttp/3.15","playerType":2,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}"},
{"name":"YanG•直播","type":0,"url":"https://tv.iill.top/m3u/Live","ua": "okhttp/3.15","playerType":2},
{"name":"YanG•体育","type":0,"url":"https://tv.iill.top/m3u/Sport","ua": "okhttp/3.15","playerType":2},
{"name":"范明明•ipv6","type":0,"url":"https://live.fanmingming.com/tv/m3u/ipv6.m3u","playerType":2,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo":"https://logo.wyfc.qzz.io/{name}.png"},
{"name":"YueChan•综合","type":0,"url":"https://github.moeyy.xyz/https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u","playerType":1,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo":"https://logo.wyfc.qzz.io/{name}.png"},
{"name":"Yoursmile•综合","type":0,"url":"https://agit.ai/Yoursmile7/TVBox/raw/branch/master/live.txt","playerType":1,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo":"https://logo.wyfc.qzz.io/{name}.png"},
{"name":"MemoryC•综合","type":0,"url":"https://ghp.ci/raw.githubusercontent.com/MemoryCollection/IPTV/refs/heads/main/itvlist.m3u","playerType":1,"ua": "okhttp/3.15","epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo": "https://logo.wyfc.qzz.io/{name}.png"},
{"name":"肥猫•综合","type":0,"url":"http://我不是.肥猫.live/TV/tvzb.txt","playerType":1,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo":"https://logo.wyfc.qzz.io/{name}.png"},
{"name":"Ray•综合","type":0,"url":"https://github.moeyy.xyz/https://raw.githubusercontent.com/dxawi/0/main/tvlive.txt","playerType":1,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo":"https://logo.wyfc.qzz.io/{name}.png"},
{"name":"俊于•综合","type":0,"url":"http://home.jundie.top:81/Cat/tv/live.txt","playerType":1,"epg":"http://epg.cdn.loc.cc/?ch={name}&date={date}","logo": "https://logo.wyfc.qzz.io/{name}.png"},
{"name":"初秋语•电台","type":0,"url":"./radio.txt","playerType":1},
{"name":"范明明•电台1","type":0,"url":"https://github.moeyy.xyz/https://raw.githubusercontent.com/fanmingming/live/main/radio/m3u/fm.m3u","playerType":1},
{"name":"范明明•电台2","type":0,"url":"https://github.moeyy.xyz/https://raw.githubusercontent.com/fanmingming/live/main/radio/m3u/index.m3u","playerType":1},
{"name":"16万•MV","type":0,"url":"https://github.moeyy.xyz/https://raw.githubusercontent.com/lystv/short/main/影视/tvb/MTV.txt"},
{"name":"YuanHsing•油管","type":0,"url":"https://github.moeyy.xyz/https://raw.githubusercontent.com/YuanHsing/YouTube_to_m3u/main/youtube.m3u"}
],
"wallpaper":"https://深色壁纸.xxooo.cf/",
"sites":[
    {"key":"豆","name":"【神秘的哥哥们】","type":3,"api":"csp_DouDouGuard","indexs":1,"searchable":0,"quickSearch":0,"changeable":0},
    {"key":"玩偶","name":"👽玩偶哥哥┃4K弹幕","type":3,"api":"csp_WoGGGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto","siteUrl":"https://www.wogg.com/","danMu":"弹"}},
    {"key":"YGP","name":"🚀叨观荐影┃预告片","type":3,"api":"csp_YGPGuard","searchable":0,"quickSearch":0,"changeable":0},
    {"key":"alllive","name":"📽️一直播┃直播","type":3,"api":"csp_AllliveGuard","playerType":2,"searchable":0,"quickSearch":0,"changeable":0},
    {"key":"抠搜","name":"🍄抠抠┃搜搜","type":3,"api":"csp_KkSsGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"UC","name":"🌈优汐┃搜搜","type":3,"api":"csp_UuSsGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"原创","name":"☀原创┃不卡","type":3,"api":"csp_YCyzGuard","timeout":10,"playerType":1,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"苹果","name":"🍎苹果┃不卡","type":3,"api":"csp_LiteAppleGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"糯米","name":"🍓糯米┃秒播","type":3,"api":"csp_NmyswvGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"白白","name":"🐟白白┃秒播","type":3,"api":"csp_SbaibaiGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"文采","name":"💮文采┃秒播","type":3,"api":"csp_JpysGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"神车","name":"🐻小熊┃秒播","type":3,"api":"csp_AppSKGuard","timeout":10,"searchable":1,"quickSearch":0,"changeable":0,"ext":"rfOX1voDIQhH8epBwtCFsq+8syyZ18T30GkibomjS1xHcE9fpWU7oKJ1cO9K0M5hrnOHZ9dKjiJz5HEyTr57RZHCqunfFT7jH/mEy+uqVyo="},
    {"key":"Lib","name":"🌟立播┃秒播","type":3,"api":"csp_LibvioGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"zxzj","name":"🍊在线┃秒播","type":3,"api":"csp_ZxzjGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1,"ext":"https://www.zxzjhd.com/"},
    {"key":"厂长","name":"📔厂长┃不卡","type":3,"api":"csp_NewCzGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"溢彩","name":"💡流光┃秒播","type":3,"api":"csp_AppSxGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1,"ext":"rfOb1uAWbkRHp7hdxprG9un3+T/f19e82TUvZMviAElDfhsS/jcju7U0fe1MnN1h63CTaYIPjmEw9C0qVsgBO8um85+eGlSkG/r2q6m0DA=="},
    {"key":"比特","name":"🍄比特┃手机","type":3,"api":"csp_BttwooGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"低端","name":"⏮️低端┃外剧","type":3,"api":"csp_DdrkGuard","timeout":10,"playerType":"2","searchable":1,"quickSearch":1,"changeable":1},
    {"key":"萌米","name":"👀萌米┃多线","type":3,"api":"csp_AppTTGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":1,"ext":"uqGL1bNENEIVq+dC1p/Y9uWjuA=="},
    {"key":"兄弟","name":"🍊水星┃多线","type":3,"api":"csp_AppSxGuard","timeout":10,"searchable":1,"quickSearch":1,"filterable":1,"ext":"rfOb1uAWbkRHp7hdxprG9un3+SLP183q3ik3cJDiAwlFdF8L6SIvrvc9LrpTyIg76T7QJZdEkWNj43wiSaA0TJyQpu2IF2jsSLWFx7WkAmG40hFxJ1tI+Jf+EVG8DtoDRcNi+TtVGULnWrSz3EWnVcxR3EJhXnrwYWe1kJtNW5txuHAO"},
    {"key":"热播","name":"📺热播┃多线","type":3,"api":"csp_AppTTGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":1,"ext":"uqGL1bNENExT7/hGxpSE5qU="},
    {"key":"欢视","name":"👓欢视┃多线","type":3,"api":"csp_AppTTGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":1,"ext":"uqGL1bNENExT9fFAy5mE5qU="},
    {"key":"奥特","name":"🏝奥特┃多线","type":3,"api":"csp_AueteGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1,"ext":"https://auete.com/"},
    {"key":"贱贱","name":"🐭荐片┃P2P","type":3,"api":"csp_JPJGuard","timeout":10,"playerType":2,"searchable":1,"quickSearch":1,"changeable":0},
    {"key":"新6V","name":"🧲新6V┃磁力","type":3,"api":"csp_SixVGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":0,"ext":"https://www.xb6v.com/"},
    {"key":"Dm84","name":"🚌巴士┃动漫","type":3,"api":"csp_Dm84Guard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"Ysj","name":"🎀异界┃动漫","type":3,"api":"csp_YsjGuard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"Anime1","name":"🐾日本┃动漫","type":3,"api":"csp_Anime1Guard","timeout":10,"searchable":1,"quickSearch":1,"changeable":1},
    {"key":"926","name":"⚽926┃看球","type":3,"api":"csp_kanqiu926Guard","timeout":10,"searchable":0,"changeable":0,"style":{"type":"list"}},
    {"key":"88","name":"⚽88┃看球","type":3,"api":"csp_Sir88Guard","timeout":10,"searchable":0,"changeable":0,"style":{"type":"list"}},
    {"key":"看球","name":"⚽看球┃直播","type":3,"api":"csp_KanqiuGuard","timeout":10,"searchable":0,"changeable":0,"style":{"type":"list"}},
    {"key":"Jrsjs","name":"⚽Jrs┃球迷","type":3,"api":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/drpy2.min.js","ext":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/jrk.js","style":{"type":"list"},"timeout":10,"searchable":0,"quickSearch":0,"changeable":0},
    {"key":"酷奇","name":"🎤酷奇┃MV","type":3,"api":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/drpy2.min.js","ext":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/酷奇MV.js","style":{"type":"rect","ratio":1.597},"timeout":10,"searchable":0,"quickSearch":0,"changeable":0},
    {"key":"MTV","name":"🎧明星┃MV","type":3,"api":"csp_BiliGuard","style":{"type":"rect","ratio":1.597},"searchable":0,"quickSearch":0,"changeable":0,"ext":{"json":"https://im.feelec.com.cn/res/file.html?id=2c9a91099584ed490195f7bf50ac60b9"}},
    {"key":"虎牙直播js","name":"🐯虎牙┃直播","type":3,"api":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/drpy2.js","ext":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/huya2.js","style":{"type":"rect","ratio":1.755},"timeout":10,"playerType":"2","searchable":0,"quickSearch":0,"changeable":0},
    {"key":"斗鱼js","name":"🐟斗鱼┃直播","type":3,"api":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/drpy2.min.js","ext":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/斗鱼直播.js","style":{"type":"rect","ratio":1.755},"timeout":10,"playerType":"2","searchable":0,"quickSearch":0,"changeable":0},
    {"key":"有声小说js","name":"🎧有声┃小说","type":3,"api":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/drpy2.min.js","ext":"https://gh-proxy.net/https://raw.githubusercontent.com/fantaiying7/EXT/refs/heads/main/有声小说吧.js","style":{"type":"rect","ratio":1},"timeout":10,"searchable":0,"quickSearch":0,"changeable":0},
    {"key":"Aid","name":"🚑急救┃教学","type":3,"api":"csp_FirstAidGuard","searchable":0,"quickSearch":0,"changeable":0,"style":{"type":"rect","ratio":3.8}},
    {"key":"YpanSo","name":"🐟盘她┃三盘","type":3,"api":"csp_YpanSoGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"xzso","name":"👻盘它┃三盘","type":3,"api":"csp_XzsoGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"米搜","name":"🦋米搜┃夸父","type":3,"api":"csp_MIPanSoGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"夸搜","name":"😻夸搜┃夸父","type":3,"api":"csp_PanSearchGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"pan":"quark","Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"Aliso","name":"🙀盘搜┃阿狸","type":3,"api":"csp_PanSearchGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"YiSo","name":"😹易搜┃阿狸","type":3,"api":"csp_YiSoGuard","searchable":1,"quickSearch":1,"changeable":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},
    {"key":"push_agent","name":"🛴手机┃推送","type":3,"api":"csp_PushGuard","searchable":0,"quickSearch":0,"ext":{"Cloud-drive":"tvfan/Cloud-drive.txt","from":"4k|auto"}},

{"key":"csp_AList","name":"AList┃网盘","type":"3","api":"csp_AList","searchable":"0","quickSearch":"0","filterable":"1","changeable":0,"ext":"./json/alist.json"},
{"key":"新6V","name":"新6V磁力┃慎用","type":3,"api":"csp_SixV","searchable":1,"quickSearch":1,"changeable":0,"ext": "http://www.xb6v.com/","timeout":60},
{"key":"百度","name":"百度┃采集","type":1,"api":"https://api.apibdzy.com/api.php/provide/vod?ac=list","searchable":1,"filterable":0,"categories":["国产动漫","日韩动漫","大陆剧","欧美剧","韩剧","日剧","动作片","喜剧片","爱情片","科幻片","恐怖片","剧情片","战争片"]},
{"key":"量子","name":"量子┃采集","type":0,"api":"https://cj.lziapi.com/api.php/provide/vod/at/xml/","searchable":1,"changeable":1,"categories":["国产动漫","日韩动漫","国产剧","韩国剧","日本剧","电影片","连续剧","综艺片","动漫片","动作片","喜剧片","爱情片","科幻片","恐怖片","剧情片","战争片","台湾剧","香港剧","欧美剧","记录片","海外剧","泰国剧","大陆综艺","港台综艺","日韩综艺","欧美综艺","欧美动漫","港台动漫","海外动漫","体育","足球","篮球","网球","斯诺克"]},
{"key":"非凡","name":"非凡┃采集","type":0,"api":"http://cj.ffzyapi.com/api.php/provide/vod/at/xml/","searchable":1,"changeable":1,"categories":["国产动漫","日韩动漫","国产剧","韩国剧","日本剧","电影片","连续剧","综艺片","动漫片","动作片","喜剧片","爱情片","科幻片","恐怖片","剧情片","战争片","香港剧","欧美剧","记录片","台湾剧","海外剧","泰国剧","大陆综艺","港台综艺","日韩综艺","欧美综艺","欧美动漫","港台动漫","海外动漫"]},
{"key":"haiwaikan","name":"海外看┃采集","type":1,"api":"https://haiwaikan.com/api.php/provide/vod","searchable":1,"changeable":1},
{"key":"暴風","name":"暴風┃采集","type":1,"api":"https://bfzyapi.com/api.php/provide/vod","searchable":1,"changeable":1},
{"key":"索尼","name":"索尼┃采集","type":1,"api":"https://suoniapi.com/api.php/provide/vod","searchable":1,"changeable":1},
{"key":"快帆","name":"快帆┃采集","type":1,"api":"https://api.kuaifan.tv/api.php/provide/vod","searchable":1,"changeable":1},

{"key":"drpy_js_360影视","name":"官源┃360[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/360影视.js"},
{"key":"drpy_js_奇珍异兽","name":"官源┃爱奇艺[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/奇珍异兽.js"},
{"key":"drpy_js_百忙无果","name":"官源┃芒果[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/百忙无果.js"},
{"key":"drpy_js_腾云驾雾","name":"官源┃腾讯[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/腾云驾雾.js"},
{"key":"drpy_js_菜狗","name":"官源┃搜狗[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/菜狗.js"},
{"key":"drpy_js_优酷","name":"官源┃优酷[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/优酷.js"},
{"key":"drpy_js_我的哔哩","name":"弹幕┃我的哔哩[js]","type":3,"api":"./lib/drpy2.min.js","style":{"type":"rect","ratio":1.597},"changeable":0,"ext":"./js/我的哔哩.js"},
{"key":"drpy_js_哔哩直播","name":"弹幕┃哔哩直播[js]","type":3,"api":"./lib/drpy2.min.js","style":{"type":"rect","ratio":1.597},"changeable":0,"ext":"./js/哔哩直播.js"},
{"key":"drpy_js_JustLive","name":"直播┃JustLive[js]","type":3,"api":"./lib/drpy2.min.js","style":{"type":"rect","ratio":1.597},"changeable":0,"ext":"./js/JustLive.js"},
{"key":"drpy_js_斗鱼直播","name":"直播┃斗鱼[js]","type":3,"api":"./lib/drpy2.min.js","style":{"type":"rect","ratio":1.597},"changeable":0,"ext":"./js/斗鱼直播.js"},
{"key":"drpy_js_虎牙直播","name":"直播┃虎牙[js]","type":3,"api":"./lib/drpy2.min.js","style":{"type":"rect","ratio":1.597},"changeable":0,"ext":"./js/虎牙直播.js"},
{"key":"drpy_js_童趣","name":"少儿┃童趣[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/童趣.js"},
{"key":"drpy_js_兔小贝","name":"少儿┃兔小贝[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/兔小贝.js"},
{"key":"drpy_js_AnFuns","name":"动漫┃AnFuns[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/AnFuns.js"},
{"key":"drpy_js_NT动漫","name":"动漫┃NT动漫[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/NT动漫.js"},
{"key":"drpy_js_NyaFun","name":"动漫┃NyaFun[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/NyaFun.js"},
{"key":"drpy_js_i275听书","name":"听书┃i275听书[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"style":{"type":"rect","ratio":1},"ext":"./js/i275听书.js"},
{"key":"drpy_js_爱上你听书网","name":"听书┃爱上你听书[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"style":{"type":"rect","ratio":1},"ext":"./js/爱上你听书网.js"},
{"key":"drpy_js_博看听书","name":"听书┃博看听书[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"style":{"type":"rect","ratio":1},"ext":"./js/博看听书.js"},
{"key":"有声小说js","name":"听书┃有声小说[js]","type":3,"api":"./lib/drpy2.min.js","ext":"./js/有声小说吧.js","style":{"type":"rect","ratio":1},"searchable": 0,"quickSearch": 0,"changeable":0},
{"key":"drpy_js_评书随身听","name":"评书┃评书随身听[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/评书随身听.js"},
{"key":"drpy_js_相声随身听","name":"相声┃相声随身听[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/相声随身听.js"},
{"key":"drpy_js_好趣网","name":"电视┃好趣网[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"style":{ "type":"oval", "ratio":1.1 },"ext":"./js/好趣网.js"},
{"key":"drpy_js_广播迷FM","name":"广播┃广播迷FM[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/广播迷FM.js"},
{"key":"drpy_js_蜻蜓FM","name":"广播┃蜻蜓FM[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/蜻蜓FM.js"},
{"key":"drpy_js_DJ音乐","name":"音频┃DJ音乐[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/DJ音乐.js"},
{"key":"drpy_js_短视频","name":"聚合┃短视频[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/短视频.js"},
{"key":"drpy_js_酷6网","name":"聚合┃酷6网[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/酷6网.js"},
{"key":"drpy_js_网易公版影像","name":"聚合┃网易公版[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/网易公版影像.js"},
{"key":"drpy_js_酷奇MV","name":"MV┃酷奇[js]","type":3,"api":"./lib/drpy2.min.js","changeable":0,"ext":"./js/酷奇MV.js"},

{"key":"bb","name":"配置接口完全免费","type":3,"api":"./lib/drpy2.min.js","ext":"./js/drpy.js"},
{"key":"cc","name":"请勿相信视频中任何广告","type":3,"api":"./lib/drpy2.min.js","ext":"./js/drpy.js"}
],
"parses":[
{"name":"Json聚合","type":3,"url":"Demo"},
{"name":"虾米","type":0,"url":"https://jx.xmflv.com/?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","sohu","搜狐","letv","乐视","mgtv","芒果","imgo","rx","ltnb","bilibili","1905","xigua"]}},
{"name":"PM","url":"https://www.playm3u8.cn/jiexi.php?url=","type":0,"ext":{"flag":["qiyi","imgo","爱奇艺","奇艺","qq","腾讯","youku","优酷","pptv","PPTV","letv","乐视","leshi","bilibili","哔哩哔哩","哔哩","mgtv","芒果","sohu","xigua","fun","风行"],"header":{"User-Agent":"Mozilla/5.0"}},"header":{"User-Agent":"Mozilla/5.0"}},
{"name":"m3u8","type":0,"url":"https://jx.m3u8.tv/jiexi/?url="},
{"name":"8090","url":"https://www.8090.la/8090/?url=","type":0,"ext":{"flag":["qiyi","imgo","爱奇艺","奇艺","qq","腾讯","youku","优酷","pptv","PPTV","letv","乐视","leshi","bilibili","哔哩哔哩","哔哩","mgtv","芒果","sohu","xigua","fun","风行"],"header":{"User-Agent":"Mozilla/5.0"}},"header":{"User-Agent":"Mozilla/5.0"}},
{"name":"看看","type":0,"url":"https://jx.m3u8.pw/?url="},
{"name":"咸鱼","type":0,"url":"https://jx.xyflv.cc/?url=","ext":{"header":{"user-agent":"Mozilla/5.0(Linux;Android13;V2049ABuild/TP1A.220624.014;wv)AppleWebKit/537.36(KHTML,likeGecko)Version/4.0Chrome/116.0.0.0MobileSafari/537.36","referer":"https://www.xyflv.cc/"}}},
{"name":"云解析","type":0,"url":"https://jx.yparse.com/index.php?url=","ext":{"header":{"user-agent":"Mozilla/5.0(Linux;Android13;V2049ABuild/TP1A.220624.014;wv)AppleWebKit/537.36(KHTML,likeGecko)Version/4.0Chrome/116.0.0.0MobileSafari/537.36"}}},
{"name":"爱豆","type":0,"url":"https://jx.aidouer.net/?url=","ext":{"header":{"user-agent":"Mozilla/5.0(Linux;Android13;V2049ABuild/TP1A.220624.014;wv)AppleWebKit/537.36(KHTML,likeGecko)Version/4.0Chrome/116.0.0.0MobileSafari/537.36","referer":"https://jiejie.uk/"}}},
{"name":"巧技","type":1,"url":"http://pan.qiaoji8.com/tvbox/neibu.php?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","sohu","搜狐","letv","乐视","mgtv","芒果","tnmb","seven","bilibili","1905"],"header":{"User-Agent":"okhttp/4.9.1"}}},
{"name":"巧技二","type":1,"url":"http://pan.qiaoji8.com/tvbox/gouzi.php?url=","ext":{"flag":["qq","腾讯","qiyi","爱奇艺","奇艺","youku","优酷","sohu","搜狐","letv","乐视","mgtv","芒果","tnmb","seven","bilibili","1905","NetFilx"],"header":{"User-Agent":"okhttp/4.9.1"}}}
],
"flags":["youku","优酷","优 酷","优酷视频", "qq","腾讯","腾 讯","腾讯视频", "iqiyi", "qiyi","奇艺","爱奇艺","爱 奇 艺", "m1905", "xigua", "letv","leshi","乐视","乐 视", "sohu","搜狐","搜 狐","搜狐视频", "tudou","mgtv","芒果","imgo","芒果TV","芒 果 T V", "bilibili","哔 哩","哔 哩 哔 哩","SPA","YuMi-vip","pptv","PPTV","ltnb","rx","SLYS4k","tucheng","BYGA","luanzi","dxzy","QEYSS","aliyun","AliS","122","chuangying","CL4K","xfyun","wuduzy","wasu","renrenmi","ppayun","haiwaikan","cool","dbm3u8","xmm","funshion","ruyi1080","ruyib1080"],
"doh":[{"name":"Google","url":"https://dns.google/dns-query","ips":["8.8.4.4","8.8.8.8"]},{"name":"Cloudflare","url":"https://cloudflare-dns.com/dns-query","ips":["1.1.1.1","1.0.0.1","2606:4700:4700::1111","2606:4700:4700::1001"]},{"name":"AdGuard","url":"https://dns.adguard.com/dns-query","ips":["94.140.14.140","94.140.14.141"]},{"name":"DNSWatch","url":"https://resolver2.dns.watch/dns-query","ips":["84.200.69.80","84.200.70.40"]},{"name":"Quad9","url":"https://dns.quad9.net/dns-quer","ips":["9.9.9.9","149.112.112.112"]}],
"rules":[
{"name":"kk","hosts":["kuaikan"],"regex":["5","20.123","20.167","#EXT-X-DISCONTINUITY\\r*\\n*((?!#EXT-X-DISCONTINUITY)[\\s\\S])*?#EXT-X-KEY:METHOD((?!#EXT-X-DISCONTINUITY)[\\s\\S])*?#EXT-X-DISCONTINUITY"]},
{"name":"yqk","hosts":["yqk"],"regex":["18.4","15.1666","#EXT-X-DISCONTINUITY\\r*\\n*((?!#EXT-X-DISCONTINUITY)[\\s\\S])*?#EXT-X-CUE-OUT((?!#EXT-X-DISCONTINUITY)[\\s\\S])*?#EXT-X-CUE-IN"]},
{"name":"sn","hosts":["suonizy"],"regex":["#EXTINF.*?\\s+.*?original.*?\\.ts\\s+","15.1666","15.2666","16.3333","15.266667"]},
{"name":"bf","hosts":["bfzy"],"regex":["#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:3,[\\s\\S]*?#EXT-X-DISCONTINUITY"]},
{"name":"xx","hosts":["aws.ulivetv.net"],"regex":["#EXT-X-DISCONTINUITY\\r*\\n*#EXTINF:8,[\\s\\S]*?#EXT-X-DISCONTINUITY"]},
{"name":"lz","hosts":["vip.lz","hd.lz","v.cdnlz","yzzy1.play"],"regex":["18.5333","19.52","18.6666"]},
{"name":"ff","hosts":["vip.ffzy","hd.ffzy","ffzy"],"regex":["25.0666","25.08","20.52","25.1","25.1999"]},
{"name":"hs","hosts":["huoshan.com"],"regex":["item_id="]},
{"name":"dy","hosts":["douyin.com"],"regex":["is_play_url="]},
{"name":"nm","hosts":["toutiaovod.com"],"regex":["video/tos/cn"]},
{"name":"cl","hosts":["magnet"],"regex":["最 新","直 播","更 新"]}
]
};

    // 返回一个 Response 对象，并设置正确的 Content-Type
    return new Response(JSON.stringify(tvboxFtyAPIJsonData), {
      headers: {
        "Content-Type": "application/json"
      }
    });
  },
};

```



# github创建仓库及提交
---
![image-20260729154524486](.\images\image-20260729154524486.png)



```powershell

$ git config --global user.name "angyuang"
>> git config --global user.email "angyuang@163.com"
$ git remote add origin https://github.com/angyuang/tvbox_cloudflare.git
$ git branch -M main
$ git push -u origin main
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 16 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (15/15), 27.87 KiB | 5.57 MiB/s, done.
Total 15 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/angyuang/tvbox_cloudflare.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

```

# 关联cloudflare
---

登录cloudflare-->构建-->计算-->Workers 和 Pages-->创建新应用

![image-20260729154958106](.\images\image-20260729154958106.png)

![image-20260729155016999](.\images\image-20260729155016999.png)

![image-20260729155038000](.\images\image-20260729155038000.png)

![image-20260729155111250](.\images\image-20260729155111250.png)

![image-20260729155132980](.\images\image-20260729155132980.png)

![image-20260729155145136](.\images\image-20260729155145136.png)

![image-20260729161953211](.\images\image-20260729161953211.png)



![image-20260729162115788](.\images\image-20260729162115788.png)

# 域名配置

---



![image-20260729162207807](.\images\image-20260729162207807.png)

![image-20260729162648407](.\images\image-20260729162648407.png)

![image-20260729162714485](.\images\image-20260729162714485.png)



![image-20260729162446356](.\images\image-20260729162446356.png)



# 自定义cloudflareAPI令牌

---



![image-20260729161705815](.\images\image-20260729161705815.png)



![image-20260729161509605](.\images\image-20260729161509605.png)

![image-20260729161533207](.\images\image-20260729161533207.png)

![image-20260729161556113](.\images\image-20260729161556113.png)

# 域名托管到cloudflare

---



![image-20260729163155136](.\images\image-20260729163155136.png)

![image-20260729163217144](.\images\image-20260729163217144.png)

![image-20260729163114684](.\images\image-20260729163114684.png)

## 域名配置dns

![image-20260729163309453](.\images\image-20260729163309453.png)

## 域名注册商配置cloudflare的dns

> carioca.ns.cloudflare.com
>
> jermaine.ns.cloudflare.com

![image-20260729163451507](.\images\image-20260729163451507.png)

![image-20260729163018773](.\images\image-20260729163018773.png)
