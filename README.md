# 免责声明
OK影视、TVBox、猫影视配置文件。所有资源均来自于各路大神无私分享，如有侵权，请联系删除。

所有以任何方式查看本仓库内容的人、或直接或间接使用本仓库内容的使用者都应仔细阅读此声明。本仓库管理者保留随时更改或补充此免责声明的权利。一旦使用、复制、修改了本仓库内容，则视为您已接受此免责声明。

本仓库管理者不能保证本仓库内容的合法性、准确性、完整性和有效性，请根据情况自行判断。本仓库内容，仅用于测试和学习研究，禁止用于商业用途，不得将其用于违反国家、地区、组织等的法律法规或相关规定的其他用途，禁止任何公众号、自媒体进行任何形式的转载、发布，请不要在中华人民共和国境内使用本仓库内容，否则后果自负。

本仓库内容中涉及的第三方硬件、软件等，与本仓库内容没有任何直接或间接的关系。本仓库内容仅对部署和使用过程进行客观描述，不代表支持使用任何第三方硬件、软件。使用任何第三方硬件、软件，所造成的一切后果由使用的个人或组织承担，与本仓库内容无关。

所有直接或间接使用本仓库内容的个人和组织，应 24 小时内完成学习和研究，并及时删除本仓库内容。如对本仓库内容的功能有需求，应自行开发相关功能。所有基于本仓库内容的源代码，进行的任何修改，为其他个人或组织的自发行为，与本仓库内容没有任何直接或间接的关系，所造成的一切后果亦与本仓库内容和本仓库管理者无关。
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
 7. 其他参考
 ---
 
2026在线接口源汇总贴:https://ooook.cn/3711.html
```shell
在线接口源（7月）

直播
develop202
https://gh.927223.xyz/https://raw.githubusercontent.com/develop202/migu_video/refs/heads/main/interface.txt
Kimentanm
https://gh.927223.xyz/https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u
https://ghfast.top/https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u
范明明（需开启V6网络）
https://nos.netease.com/ysf/3d75a78a0fc7ede372c03598d6d10367.m3u
综合直播
https://ghfast.top/https://raw.githubusercontent.com/develop202/migu_video/refs/heads/main/interface.txt

uz影视接口：

https://gitee.com/yimi_5/uz/raw/master/uz.png

http://88.is-great.org/8/i/27457.txt

电影天堂接口

https://gitlab.com/duomv/dzhipy/-/raw/main/index.json

点播:

http://itv666.cc/aowu/config.webp

https://zhangqun1818.serv00.net/zq/api.json

https://www.iyouhun.com/tv/my

http://shjufei.cn/fei.txt

https://www.iyouhun.com/tv/my

https://16165.kstore.vip/ceshi.txt

http://shjufei.cn/fei.txt

https://bjq.catvod.site/

https://8815.kstore.vip/tvbox/wmz 备用接口 https://raw.giteeusercontent.com/lzxw9527/jiuyue/raw/master/wmz

http://do.xo.je/i/64417165.jpg

http://fmys.top/fmys.json

https://xduo.codered.cloud/ok/api.json

http://46.207.209.www.hxyy.jiaheysyy.top/jhyy.json

https://cdn04132025.gitlink.org.cn/api/v1/repos/zikai/tvboxtg/raw/潇洒/api.json

http://tvbox.xn--4kq62z5rby2qupq9ub.top http://cjczydby.top/svip.json https://gittea.dev/frxz751113/iptv/raw/branch/main/2.json https://cnb.cool/ms511/PG/-/git/raw/main/my.json https://1405241.xyz/tv
https://bjq.catvod.site/
https://file.alexlin1688.top/my_file/tvbox/alexlin_db06/ok_m01.json

https://cnb.cool/cnlv/tv/-/git/raw/main/20000.json


https://700sjro44343.vicp.fun/eggp/qzku/tv.json
http://tvbox.王二小放牛娃.top
http://枫斗.top/tv
https://raw.liucn.cc/box/m.json
https://9280.kstore.vip/newwex.json
https://clun.top/box.json
http://fmys.top/fmys.json
https://9280.kstore.vip/wex.json
http://tvbox.xn--4kq62z5rby2qupq9ub.top/
http://ry.90sr.com/mf.json
https://my5353.com/liugongzi
https://www.ls660.com/TV/TV.json
http://u6v.cn/6vX55k
https://tvbox.pgjgr.eu.cc/
https://cnb.cool/cnlv/tv/-/git/raw/main/20000.json
https://file.alexlin1688.top/my_file/tvbox/alexlin_db06/ok_m01.json
http://do.xo.je/i/64417165.jpg http://fmys.top/fmys.json https://xduo.codered.cloud/ok/api.json http://46.207.209.www.hxyy.jiaheysyy.top/jhyy.json https://cdn04132025.gitlink.org.cn/api/v1/repos/zikai/tvboxtg/raw/潇洒/api.json

肥猫™
http://肥猫.net/tv

饭太硬™
http://www.饭太硬.cc/tv

牛二™
https://9280.kstore.vip/newwex.json

摸鱼™
http://我不是.摸鱼儿.top

东篱™
https://16151.kstore.space

澜露™
https://raw.giteeusercontent.com/hulanlu/04/raw/master/lanlu.json

嗷呜™
http://mytv6688.xyz/aowu/config.webp

HG™
https://api.hgyx.vip/hgyx.json

clun™
https://clun.top/box.json

ray™
https://raw.githubusercontent.com/dxawi/0/main/0.json

vox™
http://rihou.cc:88/demo.php

七星™
http://7337.kstore.space/qxys/禁止传播.json

传说™
https://chuanshuo.77blog.cn/tv.json

俊于™
http://home.jundie.top:81/top98.json

分享者™
https://raw.githubusercontent.com/maoystv/6/main/001.json

刺桐™
https://www.cttv.vip/ys/json/ctys.json

动漫城™
https://www.yingm.cc/dm/dm.json

南风™
https://gh-proxy.com/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json

哈基米™
https://17264.kstore.space/哈基米.png

夏夏™
https://11405.kstore.space/xiaye/qk4k.json

多多github™
https://gh-proxy.com/raw.githubusercontent.com/leevi0709/one/main/jsm.json

天天开心™
https://play.iptv365.org/天天开心/api.json

娃哈哈™
http://ll14s7fe.zjz-service.cn:20384/api/subscription/2055497520582234112/tvbox?token=baiyetv_box

宝盒™
http://宝盒接口.top

小凯™
https://jihulab.com/jyqhkd/kd/-/raw/main/kai.json

小盒子™
http://xhztv.top/xhz

小米™
https://gh-proxy.org/https://raw.githubusercontent.com/ggrrttyyiii/CatVodSpider/refs/heads/main/json/demo.json

小苹果™
https://bitbucket.org/xduo/duoapi/raw/master/xpg.json

小马™
https://szyyds.cn/tv/x.json

少儿™
https://jihulab.com/ymz1231/xymz/-/raw/main/ymshaoer

影视资源™
http://bp.tvbox.cam

心魔™
https://gh-proxy.com/raw.githubusercontent.com/yw88075/tvbox/main/yw.json

海豚™
https://ghfast.top/https://raw.githubusercontent.com/FGBLH/FG/refs/heads/main/海豚影视无18加

愿望18™
https://ghfast.top/https://raw.githubusercontent.com/yuanwangokk-1/TV-BOX/main/纯福利/纯福利.json

挺好™
https://ztha.top/TVBox/thdjk.json

时光™
https://gh-proxy.com/https://raw.githubusercontent.com/xmbjm/svip/refs/heads/main/svip.json

月光宝盒™
https://raw.githubusercontent.com/guot55/yg/refs/heads/main/ygbox.json

木鱼™
https://catbox.n13.club/jk/jsm.json

残月影视™
https://jsd.cdn.zzko.cn/gh/1771245847/TvBox/tvbox.json

沐辰™
https://php.doube.eu.org/spider/php/config.php

湘雅晴™
https://play.iptv365.org/香雅情/api.json

潇洒™
https://9877.kstore.space/ONE/one.json

玄珠™
https://jihulab.com/xuanzhuapp/xzys/-/raw/main/xzvip.json

玉玉™
http://150.158.112.123/jar/ce3.json

真六™
https://cccimg.com/down.php/7d1f30263b3f2bf3deda2d7faeef4844.zhen6

真心™
https://cnb.cool/fish2018/zx/-/git/raw/master/FongMi.json

短剧™
https://cnb.cool/fish2018/duanju/-/git/raw/main/tvbox.json

秋水™
http://live.shqsy.com/qstv.json

菜妮丝™
https://tv.xn--yhqu5zs87a.top

裤老™
https://raw.githubusercontent.com/Jsnzkpg/Jsnzkpg/Jsnzkpg/Jsnzkpg2

在线接口源（5月）

一、影视主接口（多仓 / 单仓 / 综合）

🟢南风接口 https://gh-proxy.net/https://raw.githubusercontent.com/yoursmile66/TVBox/refs/heads/main/XC.json

🔴刘 673 仓 https://fastly.jsdelivr.net/gh/liu673cn/box@main/m.json
🟡XYQ 接口 https://raw.kkgithub.com/xyq254245/xyqonlinerule/main/XYQTVBox.json
🟢小盒子 4K http://xhztv.top/4k.json
🔴凯速备用 https://6800.kstore.vip/fish.json
🟡4K 影视仓 http://api.v6x.wht.dgwht.top/text/38eb027069d4a621/6c99aa0391877221
🟢主用多仓 https://wget.la/https://github.com/2124662895/2026cbdva/blob/main/xfnn.json
🔴备用多仓 1 https://gh.jasonzeng.dev/https://raw.githubusercontent.com/2124662895/yydhj/mainvhh/dfvdv.json

🟡潇洒多仓 https://9877.kstore.space/AnotherDS/api.json

🟢潇洒单线 https://9877.kstore.space/AnotherD/api.json

🔴小虎斑 http://hb. 小虎斑.site:25252/

🟡OK 接口 http://ok321.top/tv

🟢巧计接口 http://cdn.qiaoji8.com/tvbox.json

🔴稳定 4K http://v-dragon.com.hk/4k/

🟡4K 接口 http://tv.4kbox.top/4k/index.php

🟢茴香 4K https://12523.kstore.space/hx.json

🔴如意接口 https://gitee.com/wynp/ys/raw/master/yc.json

🟡澜露接口 https://gitee.com/hulanlu/04/raw/master/lanlu.json

🟢PG 在线 https://www.252035.xyz/p/jsm.json

🔴PG 备用 https://ghfast.top/https://raw.githubusercontent.com/debaters6/XYQ/master/0821.json

🟡潮哥接口 https://catbox.n13.club/jk/jsm.json

🟢真心接口 https://www.252035.xyz/z/FongMi.json

🔴夏夏 4K https://11405.kstore.space/xiaye/qk4k.json

🟡爱吃鬼 http://121.40.174.45:1777/2509/爱吃鬼.json

🟢学习类 http://www.su7.run/

🔴小哥哥 http://47.96.82.41:8/api.json

🟡蓝天 4K http://103.163.47.120:666/蓝天 / 蓝天解析 1.php

🟢刺桐自营 https://www.cttv.vip/ys/json/ctys.json

🔴小荷接口 https://jihulab.com/z-blog/xh2/-/raw/main/t.json

🟡木木接口 https://gitee.com/bbstudou/tvbo/raw/master/11tv.json

🟢裹柳接口 https://fastly.jsdelivr.net/gh/ls125781003/dmtg@master/zy.json

🔴巧儿接口 http://pandown.pro/tvbox/tvbox.json

🟡小米接口http://mitvbox.xyz/%E5%B0%8F%E7%B1%B3/DEMO.json

🟢玄珠接口 https://jihulab.com/xuanzhuapp/xzys/-/raw/main/xzvip.json

🔴聚玩盒子 http://xhztv.top/xhz/

🟡驸马影视 http://fmys.top/fmys.json

🟢一哥接口 http://ficfac.com/ijia/app.json

🔴维她奶 https://d.kstore.dev/download/4071/api/api.json

🟡TV 家庭 https://tv.nxog.top/m/111.php?ou=公众号欧歌 app&mz=index&jar=index&123&b=tv

🟢俊佬接口 http://home.jundie.top:81/top98.json

🔴4K 高清 https://11405.kstore.space/xiaye/4k1.json

🟡高清免扫 https://11405.kstore.space/xiaye/1080.json

🟢快龙资源 https://gitee.com/sd-live/zb/raw/master/js.json

🔴大佬接口 https://tv.203511.xyz/0821.json

🟡龙潭接口 https://gitee.com/hu-congrong/ltcw/raw/main/cbh.json

🟢龙潭音乐 https://d.kstore.dev/download/6651/api.json

🔴小橙子 4K https://git.acwing.com/xcz/xcz/-/raw/master/xcz.json

🟡宝盒 4K http:// 宝盒接口.top

🟢饭太硬 http://www.饭太硬.com/tv

🔴放牛娃 http://tvbox.xn--4kq62z5rby2qupq9ub.top/

🟡宝盒视界https://ghproxy.net/https://raw.githubusercontent.com/guot55/yg/main/box%E5%8E%9F.json

🟢扶摇 4K http://svipjx.shanhaiguanwu.com/A4K.json

🔴盒子迷 https:// 盒子迷.top/ 禁止贩卖

🟡D佬接口 https://download.kstore.space/download/2883/nzk/nzk0722.json

🟢万家影视 http://47.108.190.232:666/api/index/store?id=14&appid=95210

🔴神秘大佬 https://gitee.com/sydl2/bhmb/raw/master/ygbh.json

🟡教育专线 1 http://box.nihaohezi.com/app/hzjy.json

🟢教育专线 2 https://jihulab.com/bhjk1/vip/-/raw/main/vip.json

🔴宇静鸣 https://gitee.com/enjoy_5_0/gg/raw/vip/gz.json

🟡春盈接口 https://cdn09022024.gitlink.org.cn/api/v1/repos/hailin/aishangtv5/raw/tvbox%2Faishang.json?ref=master&access_token=23b93fc08ea0b7793ba24a7e0cb0041b64929cee

🟢蓝天白云https://gitee.com/ltby1/vip/raw/master/%E8%93%9D%E5%A4%A9%E7%99%BD%E4%BA%91.json

🔴柒豪 4Khttp://38.165.20.168/%E6%9F%92%E8%B1%AA4K.json

🟡天神 LY https://codeberg.org/froggy123/yydf2025/raw/branch/main/api.json

🟢4K 影视 https://gitee.com/zxj77/mao/raw/master/xj.json

🔴空空 4K https://kong88.dpdns.org/4k.json

🟡壹米影视 http://xn--hwtam458y.icu/%E5%A3%B9%E7%B1%B3/yimi.json

🟢幸福接口 http://xn--hwtam458y.icu/%E5%9B%BD%E5%BA%86%E5%B9%B8%E7%A6%8F/hyhr.json

🔴天微七星 https://7337.kstore.space/qxys/%E7%A6%81%E6%AD%A2%E4%BC%A0%E6%92%AD.json

🟡小龙短剧 https://gitee.com/dxl900109/yyds/raw/master/%E5%B0%8F%E9%BE%99%E7%9F%AD%E5%89%A7.json

🟢东哥接口 https://gitee.com/dong2274560336/film-and-television-interface/raw/master/fty.json

🔴鸟叔接口 https://raw.githubusercontent.com/laozi4vip/JellyZYC/main/niaoshu/tongyong.json

🟡菜妮丝 https://tv. 菜妮丝.top

🟢运输车 VIP http://530.my3v.work/hxck.json

🔴影探 4K http://www.lyyytv.cn/yt/yt.json

🟡优质接口 https://jihulab.com/yueer/yueera/-/raw/main/11.17/yueer.json

🟢绿茶影院 http://550.3vcn.work/cbh.json

🔴私人影院 http://550.3vcn.work/xj.json
🟡果冻自用 https://gitee.com/laozi4vip/myysjk/raw/master/jkwj/jelly.json
🟢龙伊线路 https:// 龙伊.top
🔴花花公子 https://d.kstore.dev/download/12020/t4.json
🟡电视魔盒 https://chuanshuo.77blog.cn/tv.json
🟢金鹰接口 http://550.3vcn.work/wdjyys.json
🔴青龙接口 https://gitee.com/yiwu369/6758/raw/master/1.json
🟡环宇轩 https://6492.kstore.space/xnf/xnf.jso
🔴星河 4K http://116.196.116.76/tv
🟡楞牛哥 http://lengniuge.cf/yingshi
🟢霜辉月明 https://ghproxy.com/raw.githubusercontent.com/lm317379829/PyramidStore/pyramid/py.json
🔴QIST 接口 https://gh-proxy.com/https://raw.githubusercontent.com/qist/tvbox/master/jsm.json
🟡0202 接口 http://150.158.112.123/bb/0202.txt
🟢宝盒 VIP https://3043.kstore.space/bhvip/bh/box.json
🔴月亮 V https://xn--3lq960d.v.nxog.top/api.php?id=2
🟡欧歌接口 http://tv.nxog.top/m/
🟢摸鱼 UZ http://xn--ihqu10cn4c.xn--v4q818bf34b.com/UZ/DEMO.json
🔴喵影视 http://www.meowtv.vip/tvbox.json
🟡胜寒接口 https://ghfast.top/https://raw.githubusercontent.com/hanhan8127/TVBox/main/hanXC.json
🟢二哈接口 https://ghfast.top/https://raw.githubusercontent.com/2hacc/TVBox/main/tvbox.json
二、特色专用接口

🔴摸鱼接口 http:// 我不是。摸鱼儿.com
🟡肥猫接口 http:// 肥猫.com
🟢宝盒接口 http://mzjk.top/禁止贩卖
🔴戏曲接口 http://mzrjk.top/戏曲
🟡学习接口 http://mzrjk.top/学习
🟢音乐接口 http://mzrjk.top/音乐

🔴Jack老师http://ok213.top/tv
三、游魂网络专线

🔴游魂 fty https://www.iyouhun.com/tv/fty

🟡游魂 fxz https://www.iyouhun.com/tv/fxz

🟢游魂 fm https://www.iyouhun.com/tv/fm

🔴游魂 hzm https://www.iyouhun.com/tv/hzm

🟡游魂 xs https://www.iyouhun.com/tv/xs

🟢游魂 dh https://www.iyouhun.com/tv/dh
四、本地包 & 工具

🔴柒豪本地包 https://gitee.com/qihaoyyds/qihao/raw/master/本地包.zip

🟡潇洒单线包 https://gitee.com/PizazzXS/another-d/raw/master/单线路.zip

🟢潇洒多线包 https://gitee.com/PizazzXS/another-d/raw/master/多线路.zip

🔴壁纸接口 http://127.0.0.1:9978/proxy?do=wallpaper
五、开源项目 & 仓库

🔴TVBoxOS https://github.com/q215613905/TVBoxOS

🟡CatVodTVOSC https://github.com/kensonmiao/CatVodTVOSC

🟢pluto-player https://github.com/pluto-player/updates

🔴takagen99 https://github.com/takagen99/TVBoxOSC

🟡o0HalfLife0o https://github.com/o0HalfLife0o/TVBoxOSC

🟢clanTV https://github.com/clanTV/clanTV

🔴FongMi https://github.com/FongMi/TV

🟡BearTV https://github.com/haha459862/BearTV

🟢官方 TVBoxOSC https://github.com/CatVodTVOfficial/TVBoxOSC

🔴tv-player https://github.com/tv-player
在线接口源（3月）

牛二接口源更新

OK萤石（安卓专用）接口：

牛二(新街口) https://9280.kstore.vip/newwex.json

牛二(中文top) http://tvbox.王二小放牛娃.top

牛二(常规top) http://tvbox.xn--4kq62z5rby2qupq9ub.top

牛二(1数字xyz) http://tv.999888987.xyz/

牛二(2数字xyz) http://tv.999888123.xyz/     

牛二(凯速) https://9280.kstore.vip/wex.json

M壳 猫壳 羊壳（ios专用）街口：

http://wexfnw:wexfnw@cat.xn--4kq62z5rby2qupq9ub.top/index.js.md5

http://wexfnw:wexfnw@cat.999888987.xyz/index.js.md5

http://wexfnw:wexfnw@cat.999888123.xyz/index.js.md5

M壳 羊壳专用街口：

https://9280.kstore.vip/cat/index.js.md5

直播源：

http://ko.zoho.to/ii/15997.txt

https://gitee.com/yimi321/tv/raw/master/tv.png$壹米直播||https://gitee.com/yimi321/tv/raw/master/tv1.png$全网通随缘||https://gitee.com/yimi321/tv/raw/master/iptv6.png$壹米ipv6||https://fy.188766.xyz/?ip=211.101.246.236$壹米冰茶

http://ku9.fr.to/ku9/1768502278.txt

https://raw.githubusercontent.com/develop202/migu_video/refs/heads/main/interface.txt

http://ko.zoho.to/ii/%E6%B8%AF%E6%BE%B3%E5%8F%B0.txt

http://ko.zoho.to//ii/72183.txt

影视接口源：

https://fastly.jsdelivr.net/gh/liu673cn/box@main/m.json

https://raw.kkgithub.com/xyq254245/xyqonlinerule/main/XYQTVBox.json

蝶儿飞

http://xhztv.top/4k.json

接口：
http://我不是.摸鱼儿.com
浏览器访问接口获取摸鱼全部资源
备用接口：
http://我不是.摸鱼儿.top
凯速（羊壳peek安卓专用）：
https://6800.kstore.vip/fish.json

摸鱼最新接口接口：

http://我不是.摸鱼儿.com

浏览器访问接口获取摸鱼全部资源备用接口：http://我不是.摸鱼儿.top

凯速备用：https://6800.kstore.vip/fish.json壁纸：

http://127.0.0.1:9978/proxy?do=wallpaper

注意：壁纸依托内置go服务，可自动识别屏幕匹配合适的内容

默认订阅源 iptv-api：
https://gitee.com/mytv-android/iptv-api/raw/master/output/result.m3u
WebView订阅源：
https://gitee.com/mytv-android/iptv-api/raw/master/output/webview.m3u
🔵4k影视仓：

http://api.v6x.wht.dgwht.top/text/38eb027069d4a621/6c99aa0391877221

🔵主用接口多仓:

https://wget.la/https://github.com/2124662895/2026cbdva/blob/main/xfnn.json

🔵备用多仓1:

https://gh.jasonzeng.dev/https://raw.githubusercontent.com/2124662895/yydhj/mainvhh/dfvdv.json

🔵柒豪本地包【随时随地更新】

https://gitee.com/qihaoyyds/qihao/raw/master/本地包.zip

🔵全球电视：

http://ku9.fr.to/ku9/1768502278.txt

🔵游魂网络：

https://www.iyouhun.com/tv/fty

https://www.iyouhun.com/tv/fxz

https://www.iyouhun.com/tv/fm

https://www.iyouhun.com/tv/hzm

https://www.iyouhun.com/tv/xs

https://www.iyouhun.com/tv/dh

🔵潇洒多仓：

https://9877.kstore.space/AnotherDS/api.json

🔵潇洒单线：

https://9877.kstore.space/AnotherD/api.json

🔵小虎斑接口：

http://hb.小虎斑.site:25252/仅供测试

🔵肥猫线路：

http://肥猫.com/

🔵摸鱼接口①：

http://我不是.摸鱼儿.top

🔵牛二线路：

http://tvbox.王二小放牛娃.top

🔵OK接口：

http://ok321.top/tv

🔵巧计接口：

http://cdn.qiaoji8.com/tvbox.json

🔵4K接口：

http://v-dragon.com.hk/4k/

🔵4K接口：

http://tv.4kbox.top/4k/index.php

🔵茴香4k：

https://12523.kstore.space/hx.json

🔵如意接口:

https://gitee.com/wynp/ys/raw/master/yc.json

🔵澜露接口：

https://gitee.com/hulanlu/04/raw/master/lanlu.json

PG在线

https://www.252035.xyz/p/jsm.json

https://ghfast.top/https://raw.githubusercontent.com/debaters6/XYQ/master/0821.json

https://catbox.n13.club/jk/jsm.json

https://9280.kstore.vip/newwex.json

真心接口

https://www.252035.xyz/z/FongMi.json

直播源

https://ghfast.top/https://raw.githubusercontent.com/develop202/migu_video/refs/heads/main/interface.txt

在线接口源（2月）

★巧儿多仓：

http://pandown.pro/tvbox/tvbox.json

★分享单仓：

https://github.moeyy.xyz/https://raw.githubusercontent.com/maoystv/6/main/000.json

★匿名单仓：

https://12586.kstore.space/123.txt

★天微单仓：

https://qixing.myhkw.com/DC.txt

★星辰单仓：

https://fmbox.cc/

★欧歌单仓：

https://o.nxog.top/nxog/ou1.php

★多多单仓：

https://bitbucket.org/xduo/cool/raw/main/line.json

★匿名多仓：

https://12586.kstore.space/123.json

★OK单仓（激活码：3508）：

http://ok321.top/ok

在线接口源单仓多线路

一、饭太硬

🔴饭太硬主接口1 http://www.饭太硬.net/tv

🟡饭太硬主接口2 http://www.饭太硬.com/tv

🟢饭太硬备用1 http://www.饭太硬.xyz/tv

🔴饭太硬备用2 http://fty.xxooo.cf/tv

🟡饭太硬备用3 http://fty.888484.xyz/tv

🟢饭太硬备用4 http://fty.333232.xyz/tv
二、江苏专用

🔴江苏专用接口 https://gitee.com/xxoooo/fan/raw/master/in.bmp
三、肥猫

🟡肥猫主接口 http://肥猫.com/

🟢肥猫备用接口 http://hello.肥猫.com
四、王二小放牛娃

🔴王二小主接口1 http://tv.999888987.xyz/

🟡王二小主接口2 http://tvbox.王二小放牛娃.top/

🟢王二小主接口3 http://tv.999888123.xyz/

🔴王二小防屏蔽1 https://9280.kstore.space/wex.json

🟡王二小防屏蔽2 https://d.kstore.dev/download/9280/wex.json
五、摸鱼4K

🟢摸鱼4K主接口 http://我不是.摸鱼儿.com

🔴摸鱼4K备用接口 http://我不是.摸鱼儿.top
六、榴芒电视

🟡榴芒电视接口 http://8.138.7.223/tv.txt
七、小米

🟢小米主接口 http://miqk.cc/小米/DEMO.json

🔴小米备用接口 https://mi.mpanso.me/DEMO.json
八、OK猫

🟡OK猫内部接口 http://ok321.top/tv

🟢OK猫外部接口（激活码：3844） http://ok321.top/ok
九、盒子迷

🔴盒子迷接口 https://盒子迷.top/禁止贩卖
十、天微/七星单线

🟡天微单线接口 https://7337.kstore.space/kjtv/自用测试.json

🟢七星单线1 https://11256.kstore.space/免费勿传.json

🔴七星单线2 https://11256.kstore.space/qxys/%E7%A6%81%E6%AD%A2%E4%BC%A0%E6%92%AD.json

🟡天微自用测试 https://7337.kstore.space/twvip/自用测试.json
十一、TH挺好分享

🟢TH挺好分享1 https://zthaa.top/thzx/th.json

🔴TH挺好分享2 https://zthaa.top/th/api.json
十二、宝盒没宝

🟡宝盒没宝1 http://ygbh.site/box.php

🟢宝盒没宝2 http://64.112.42.49:6688/https://raw.githubusercontent.com/guot55/yg/refs/heads/main/pg/jsm2.json
十三、木鱼

🔴木鱼接口 https://catbox.n13.club/jk/jsm.json
十四、陆城影视

🟡陆城影视接口 https://jianhancloud.cn/lcys/lcjk.json
十五、蓝天白云4K解析

🟢蓝天白云4K解析（质量较高稳定性存疑） http://103.163.47.120:666/蓝天/蓝天解析1.php

🔴蓝天自建接口 https://gitee.com/lukei7/lib/raw/Luck/%E8%87%AA%E5%BB%BA.json
十六、天神

🟡天神接口 https://gitee.com/iy-cpu/iy/raw/master/天神IY.json
十七、xiaye

🟢xiaye接口 https://11405.kstore.space/xiaye/qk4k.json
十八、无意云

🔴无意云接口（大部分需网盘扫码） https://ym.wya6.cn/
十九、潇洒

🟡潇洒接口 https://9877.kstore.space/AnotherD/api.json
二十、巧记

🟢巧记主接口 http://cdn.qiaoji8.com/tvbox.json

🔴巧记备用接口 http://pandown.pro/tvbox/tvbox.json
二十一、聚玩盒子

🟡聚玩盒子接口 http://xhztv.top/xhz
二十二、天天/天天开心

🟢天天接口 http://tv.laohu.cool/tvbox.json

🔴天天开心接口 http://rihou.cc:55/天天开心
二十三、快乐

🟡快乐接口 http://影视仓接口.top
二十四、驸马

🟢驸马主接口 http://fmys.top/fmys.json
二十五、青龙

🔴青龙接口 https://gitee.com/yiwu369/6758/raw/master/青龙/1.json
二十六、胜寒

🟡胜寒接口 https://raw.bgithub.xyz/hanhan8127/TVBox/main/hanXC.json
二十七、香雅晴/香雅情

🟢香雅晴接口 https://gh-proxy.com/https://raw.githubusercontent.com/xyq254245/xyqonlinerule/main/XYQTVBox.json
二十八、音乐类接口

🔴TG音乐（天微维护） https://7337.kstore.space/TGMTV/TGyinyue.txt

🟡DG音乐台 https://ddzb.fun/dgmusic/api.json

🟢DG戏曲 http://101.200.122.188/xiqu

🔴Nx音乐 https://pz.nxpz.xyz/tgyyc/api.json
二十九、其他热门接口

🟡短剧接口1 http://74.120.175.78/JK/XYQTVBox/dj.json

🟢短剧接口2 http://box.ufuzi.com/tv/qq/短剧频道/api.json

🔴剪影接口 https://git.acwing.com/lkq0379/zjys/-/raw/main/zjys.json

🟡白龙接口 http://124.71.189.194/a.json

🟢欧歌接口（可看直播） https://o.nxog.top/m/111.php?ou=公众号欧歌app&mz=index&jar=index&123&b=o

🔴刘伟接口 https://git.acwing.com/lw0704/66/-/raw/master/jjzx.json

🟡传说接口 https://chuanshuo.77blog.cn/tv.json

🟢南风接口 https://gh-proxy.com/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json

🔴骚零接口 https://100km.top/0

🟡少儿频道接口 https://jihulab.com/ymz1231/xymz/-/raw/main/ymshaoer
直播接口

一、核心综合直播源（通用适配）

通用zb源

https://pub.tgyes.eu.org/555.txt

✅全球直播： https://gh.catmak.name/https://raw.githubusercontent.com/wujiangliu/live-sources/refs/heads/main/全球直播.m3u

✅Guovin: https://raw.githubusercontent.com/Guovin/iptv-api/gd/output/ipv4/result.m3u

✅云影空蒙： https://ghfast.top/https://raw.githubusercontent.com/yaoxieyoulei/YYKM_assets/main/webview.m3u

✅webview： https://raw.githubusercontent.com/mytv-android/China-TV-Live-M3U8/refs/heads/main/webview.m3u

✅电视家重生： https://gh.catmak.name/https://raw.githubusercontent.com/wujiangliu/live-sources/refs/heads/main/电视家.m3u

💋黯笙爱看源: https://gitee.com/huluxiaansheng/zby1.0.1/raw/master/akxl.txt

🟡IPTV 自动更新：https://ghfast.top/https://raw.githubusercontent.com/qingtingjjjjjjj/iptv-auto-update/main/my.txt

🟢白嫖军团直播源：

http://gg.7749.org/z/0/白嫖军团.txt

🔴IPTV365 直播：https://live.iptv365.org/live.txt（含音乐欣赏内容）

🟡开心直播源：http://ttkx.cc:55/lib/kx2024.txt

🟢传说直播源：http://kkk.jjjj.jiduo.me/user/tttt/api.txt（解析失败）

🔴长青直播源：http://yuan.haitangw.net/ZB/index.json

🟡缝纫机直播：https://d.h6room.com/frjzb.txt（含央视 / 卫视 / IPV6 多类资源）

🟢拾光直播源：https://slink.ltd/https://raw.githubusercontent.com/xmbjm/TV/refs/heads/master/output/user_result.txt

🔴宝盒直播：https://mzjk.top/zb.txt

🟡宝盒直播 2：https://mzjk.top/zb1.txt

🟢自动更新直播：http://175.178.251.183:6689/live.m3u

🔴全面直播：https://mirror.ghproxy.com/https://raw.githubusercontent.com/Ftindy/IPTV-URL/main/Collect.m3u

🟡天微直播：https://7337.kstore.space/twkj/tvzb.txt

🟢春盈天下：http://xhztv.top/cytx.txt（解析失败）

🔴群友搜刮直播：http://tv.tttttttttt.top/0/群友搜刮.txt

🟡摸鱼直播：http://go.work.gd/0/moyu.txt（解析失败）

🟢金蛇直播：https://pan.7so.top/f/L7o2iQ/金蛇.txt

🔴Fmbox 直播：https://fmbox.cc/php/xc.txt（解析失败）

🟡520 直播源：https://d.kstore.dev/download/2912/520.txt（解析失败）

🟢Hanhan 直播：https://raw.bgithub.xyz/hanhan8127/TVBox/main/live.txt（含央视 / 卫视 / 港澳台资源）

🔴SCXSVIP 直播：https://g.3344550.xyz/https://raw.githubusercontent.com/SCXSVIP/TV/main/live.txt

🟡API 直播源：http://api.v6x.wht.dgwht.top/text/863de13705ddfdc2/9aa228a41ac22ae6（解析失败）

🟢SZY 直播：https://szyyds.cn/tv/live/x.txt（解析失败）

🔴驸马直播：http://fmys.top//lib/xinghuo1.0.txt

🟡电视直播：http://tv.wmdz.com/ku91311.txt

🟢推荐直播：http://zozo.myartsonline.com/0/zb2.txt

🔴Y977 直播：http://api.y977.com/iptv.txt

🟡盒子迷直播：http:// 盒子迷.top/ZB

🔴TV8 直播：https://1229.tv1288.xyz/TV8.tx

🟢长苏影视：https://gitee.com/wu-xuewei520/private/raw/master/JS/长苏影视.txt

🔴电信直播源：http://go.work.gd/1/电信直播源.txt

🟡元旦直播：http://go.work.gd/1/一锅端直播_元旦.txt

🟢苦短直播：https://12428.kstore.space/苦短直播过年版.txt

🔴央卫简洁源：https://gitee.com/wjdjxjxj/tv/raw/master/qa.txt

🟡Guovin 自动更新：https://ghproxy.net/raw.githubusercontent.com/Guovin/TV/gd/output/result.txt

🟢喵影视直播：http://meowtv.top/zb（解析失败）

🔴猫影视直播：http://www.meowtv.top/mtvzb.txt

🟡小岭直播：https://gitee.com/jin-xueling/lingl/raw/master/hu.txt

🟢暮雨直播：https://4key.cn/FP（解析失败）

🔴路小明直播：https://l.gmbbk.com/upload/62196219.txt

🟡欧歌直播：http:// 网。欧. 我爱你 /down.php/a7c9d038627e11f037adcad788da129e.txt

🟢蓝天白云：https://10085.kstore.space/蓝天白云.txt

🔴群晖松视：https://pan.jl8.top/down.php/012e419b3d29a2f141123cb324479fe4.txt

🟡最全直播：https://jihulab.com/-/snippets/5265/raw/main/.txt

🟢六维直播：http://39.101.135.137:8081/xx3.txt

🔴牛马直播：https://fel.forxhr.top:2022/down.php/f284e4942e45d20edccca6846b54c61a.txt

🟡龙直播：https://gitee.com/lumiadragon/ysc/raw/main/zhibo.txt

🟢热舞直播：https://gitee.com/hot-song-and-hot-dance_0/live-streaming—tv.txt-direct/raw/master/m3u2.txt

🔴日后直播：http://rihou.cc:567/gggg.nzk

🟡日后直播 2：http://rihou.cc:555/gggg.nzk

🟢枫叶直播：https://gitee.com/fuscloud/android-cat-vod-spider/raw/master/json/tv.text

🔴大年初三直播：https://5288.kstore.space/z.bmp（解析失败）

🟡小白直播：http://d.kstore.dev/download/11649/xiaobai.txt（含央视 1 直播源）

🟢肥羊直播：http://vv.vmhost.cc/c/zb/肥羊.txt（解析失败）

🔴肥羊直播 2：http://vv.vmhost.cc/tv/20250116直播.txt

🟡肥羊直播 3：https://fel.forxhr.top:2022/down.php/2c698a55a80aaeb547bb983910f6852c.txt
二、IPV6 专属直播源（IPV6 网络专用）

🔴IPV6 综合直播源：http://47.120.41.246:8899/zb.txt

🟡范明明直播 (IPV6)：https://live.fanmingming.cn/tv/m3u/ipv6.m3u（解析失败）

🟢菜妮丝直播 (IPV6)：https://tv. 菜妮丝.top/lives/IPv6.php

🔴尝试直播 (IPV6)：https://gh.tryxd.cn/raw.githubusercontent.com/suxuang/myIPTV/main/ipv6.m3u

🟡范明明直播 2 (IPV6)：https://mirror.ghproxy.com/https://raw.githubusercontent.com/fanmingming/live/main/tv/m3u/ipv6.m3u

🟢范明明备用 (IPV6)：https://fanmingming.com/txt?url=https://raw.githubusercontent.com/fanmingming/live/main/tv/m3u/ipv6.m3
三、港澳台及海外直播源

🔴港澳台直播源：http://8.138.7.223/live.txt

🟡凤凰资讯：http://php.jdshipin.com/TVOD/iptv.php?id=fhzx

🟢凤凰中文：http://php.jdshipin.com/TVOD/iptv.php?id=fhzw

🔴凤凰香港：http://php.jdshipin.com/TVOD/iptv.php?id=fhhk

🟡TVBS 新闻：rtmp://f13h.mine.nu/sat/tv761

🟢非凡新闻：rtmp://f13h.mine.nu/sat/tv581
四、特色系列直播源
大葱系列订阅

🔴大葱 Gather 直播：https://tv.iill.top/m3u/Gather（解析失败）

🟡大葱 MyTV：https://tv.iill.top/m3u/MyTV（解析失败）

🟢大葱 Live：https://tv.iill.top/m3u/Live（解析失败）

🔴大葱 Sport：https://tv.iill.top/m3u/Sport（解析失败）

🟡神秘订阅：https://tv.iill.top/m3u/Adult
Guovin 系列

🔴Guovin 直播源 (M3U)：https://ghproxy.cc/https://raw.githubusercontent.com/Guovin/iptv-api/gd/output/result.m3u

🟡Guovin 直播源 (TXT)：https://raw.githubusercontent.com/Guovin/iptv-api/gd/output/result.txt

🟢Guovin 自动更新：https://ghproxy.net/raw.githubusercontent.com/Guovin/TV/gd/output/result.txt
YueChan 系列

🔴YueChan APTV：https://raw.githubusercontent.com/YueChan/Live/refs/heads/main/APTV.m3u

🟡YueChan IPTV：https://mirror.ghproxy.com/https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u

🟢YueChan Global：https://raw.githubusercontent.com/YueChan/Live/refs/heads/main/Global.m3u

🔴YueChan Radio：https://raw.githubusercontent.com/YueChan/Live/refs/heads/main/Radio.m3u

🟡YueChan Radio2：https://mirror.ghproxy.com/https://raw.githubusercontent.com/YueChan/Live/main/Radio.m3u
Joevess 系列（央卫 + 地方台）

🔴Joevess 央卫 1：https://mirror.ghproxy.com/raw.githubusercontent.com/joevess/IPTV/main/home.m3u8

🟡Joevess 央卫 2：https://mirror.ghproxy.com/raw.githubusercontent.com/joevess/IPTV/main/sources/home_sources.m3u8

🟢Joevess 央卫 3：https://ghp.ci/raw.githubusercontent.com/joevess/IPTV/main/sources/home_sources.m3u8

🔴Joevess 央卫 + 地方 1：https://mirror.ghproxy.com/raw.githubusercontent.com/joevess/IPTV/main/iptv.m3u8

🟡Joevess 央卫 + 地方 2：https://mirror.ghproxy.com/raw.githubusercontent.com/joevess/IPTV/main/sources/iptv_sources.m3u8
五、纪录片专用源

🔴人与自然：http://newcntv.qcloudcdn.com/asp/hls/1200/0303000a/3/default/1425e1d505654cb48ba82b807b221193/1200.m3u8

🟡自然传奇：http://newcntv.qcloudcdn.com/asp/hls/1200/0303000a/3/default/81a1ad3a661748bfb8560c92d38204ca/1200.m3u8

🟢探索发现：http://newcntv.qcloudcdn.com/asp/hls/1200/0303000a/3/default/25137bd7c4494128bf0cba271974928f/1200.m3u8

🔴地理中国：http://newcntv.qcloudcdn.com/asp/hls/1200/0303000a/3/default/c6baf6f74bb944aeacee1065ea72c798/1200.m3u8

🟡航拍中国第一季：http://newcntv.qcloudcdn.com/asp/hls/4000/0303000a/3/default/8edf3fb6a69148ea9a7dc0b5a9d99fdb/4000.m3u8

🟢航拍中国第二季：http://newcntv.qcloudcdn.com/asp/hls/4000/0303000a/3/default/2bdfdad540b342f592f9817cb7f3b79a/4000.m3u8
六、直播中国（风景直播）

🔴直播中国主频道：https://gcalic.v.myalicdn.com/gc/wgw05_1/index.m3u8

🟡八里沟桃花湾瀑布：https://gcalic.v.myalicdn.com/gc/blg05_1/index.m3u8

🟢普陀山：https://gcalic.v.myalicdn.com/gc/pts01_1/index.m3u8

🔴丽江古城大水车：https://gcalic.v.myalicdn.com/gc/ljgcdsc_1/index.m3u8

🟡乌镇西市河：https://gcalic.v.myalicdn.com/gc/zjwzbblh_1/index.m3u8

🟢泰山主峰：https://gcalic.v.myalicdn.com/gc/taishan01_1/index.m3u8
七、音乐 / 歌曲 / DJ 专用源
经典歌曲

🔴冷漠 – 我是否也在你心中：http://antiserver.kuwo.cn/anti.s?rid=MUSIC_4378249&response=res&format=mp4&type=convert_url

🟡凤凰传奇 – 奢香夫人：http://antiserver.kuwo.cn/anti.s?rid=MUSIC_51674527&response=res&format=mp4&type=convert_url

🟢刀郎 – 西海情歌：https://vdse.bdstatic.com//628ca08719cef5987ea2ae3c6f0d2386.mp4

🔴陈瑞 – 有谁知道我在等你：http://antiserver.kuwo.cn/anti.s?rid=MUSIC_1583218&response=res&format=mp4&type=convert_url

🟡毛不易 – 借：https://vd3.bdstatic.com/mda-ii2njckdbkmmcp81//mda-ii2njckdbkmmcp81.mp4?pd=20

🟢于文文 – 体面：https://vdse.bdstatic.com//f18bdf41f28b68a1b0177fa5e5cdf8fe.mp4?authorization=bce-auth-v1%2F40f207e648424f47b2e3dfbb1014b1a5%2F2020-01-31T14%3A25%3A29Z%2F-1%2Fhost%2F1a9107b1210343ed30aa27779a042aab3d016777226b471ee5f38c8fc1e23cf1
DJ 舞曲

🔴热火斯卡拉：https://vd4.bdstatic.com/mda-nk3qfbxhf5dqpywt/sc/cae_h264/1667582665910576925/mda-nk3qfbxhf5dqpywt.mp4

🟡震撼纯电音 Drown：https://vd2.bdstatic.com/mda-mjshcpd847mhnjgj/sc/cae_h264/1635337200637124885/mda-mjshcpd847mhnjgj.mp4

🟢车载必备 DJ 串烧：https://vd3.bdstatic.com/mda-mhve4gb9hi8cstzk/1080p/cae_h264/1630319514896018158/mda-mhve4gb9hi8cstzk.mp4

🔴海来阿木 – 浪子心 (DJ 沈念版)：https://vd3.bdstatic.com/mda-mgr9s5pv0jeqbcm8/1080p/cae_h264/1627298307874491239/mda-mgr9s5pv0jeqbcm8.mp4

🟡韩可可 – 错位时空 (DJ 版)：https://vd3.bdstatic.com/mda-mgciytzb45z6z8yj/1080p/cae_h264/1626183756603775947/mda-mgciytzb45z6z8yj.mp4

🟢经典老歌 DJ 串烧：https://vd2.bdstatic.com/mda-mhwbtsnrmm6v6x5r/sc/cae_h264/1630403250895754314/mda-mhwbtsnrmm6v6x5r.mp4
八、戏曲专用源

🔴戏曲直播 1：http://l.gmbbk.com/upload/62476247.txt

🟡戏曲直播 2：http://l.gmbbk.com/upload/0713713.txt

🟢戏曲直播 3：http://101.200.122.188/xiqu

🔴DG 戏曲直播：http://101.200.122.188/dgzb.txt

🟡CCTV-11 戏曲：http://36.105.100.208:35455/gaoma/cctv11.m3u8
直播接口备用
图标	名称	地址
🔴	自用测试	https://7337.kstore.space/kjtv/自用测试.json
🟡	自主云线路	http://zizhuyun.top/yuan/zizhuyun.json
🟢	小脑斧接口	https://6492.kstore.space/xnf/xnf.json
🔴	幸福年年-4K推荐	https://11405.kstore.space/xiaye/qk4k.json
🟡	幸福年年-4K高清	https://11405.kstore.space/xiaye/4k1.json
🟢	幸福年年-高清版	https://11405.kstore.space/xiaye/1080.json
🔴	无敌凯少爷-单仓	https://gitee.com/jvftibcs-jbduyh/007/raw/master/无敌凯少爷单仓免费一接口禁止贩卖，举报贩卖有奖.json
🟡	无敌凯少爷-多仓	https://gitee.com/jvftibcs-jbduyh/007/raw/master/无敌凯少爷多仓免费接口禁止贩卖，举报贩卖有奖.json
🟢	无敌凯少爷-躺平	https://git.acwing.com/SVIP/007/-/raw/main/无敌凯少爷躺平单仓接口🈲止贩卖，举报贩卖有奖.json
🔴	综合接口	http://nn.qi-simple.top/common.json
🟡	网盘接口	http://nn.qi-simple.top/cloud.json
🟢	蓝光接口	http://nn.qi-simple.top/film.json
🔴	天神IY	https://gitee.com/iy-cpu/iy/raw/master/天神IY.json
🟡	幸福年年老接口	https://gh.jasonzeng.dev/https://raw.githubusercontent.com/2124662895/yydhj/mainvhh/2023ususiua.php
🟢	幸福年年备用接口	https://gh.jasonzeng.dev/https://raw.githubusercontent.com/2124662895/yydhj/mainvhh/xbrthx.json
🔴	青龙1080接口	https://gitee.com/yiwu369/6758/raw/master/青龙/1.json
🟡	青龙4K接口	https://gitee.com/yiwu369/6758/raw/master/青龙/2.json
🟢	白虎接口	https://gitee.com/yiwu369/6758/raw/master/白虎/白虎.json
🔴	讴歌线路	https://xn--56jc783u8uaj9fd4ae3g5r7adg8d.v.nxog.top/api.php?id=1
🟡	菜妮丝接口	https://tv.菜妮丝.top
🟢	巧技接口	http://cdn.qiaoji8.com/tvbox.json
🔴	小虎斑测试	http://hb.小虎斑.site:25252/仅供测试
🟡	潇洒接口	https://9877.kstore.space/AnotherD/api.json
🟢	总统影院1.4	https://fs-im-kefu.7moor-fs1.com/ly/4d2c3f00-7d4c-11e5-af15-41bf63ae4ea0/1738815880122/总统影院1.4.cc
🔴	饭太硬线路	http://饭太硬.com/tv
🟡	饭太硬线路2	http://www.饭太硬.com/tv
🟢	饭太硬线路3	http://www.饭太硬.net/tv
🔴	饭太硬线路4	http://www.饭太硬.xyz/tv
🟡	饭太硬线路5	http://fty.xxooo.cf/tv
🟢	摸鱼线路	http://我不是.摸鱼儿.top
🔴	有毒线路	https://tv.youdu.fan:666
🟡	小米线路1	http://www.mpanso.com/小米/DEMO.json
🟢	小米线路2	http://xhww.fun/小米/DEMO.json
🔴	王小二源1	http://tvbox.王二小放牛娃.top
🟡	王小二源2	http://tvbox.王二小放牛娃.xyz
🟢	OK杰克线路	http://ok321.top/tv
🔴	南风线路	https://agit.ai/Yoursmile7/TVBox/raw/branch/master/XC.json
🟡	神器线路	https://神器每日推送.tk/pz.json
🟢	Ray线路	https://100km.top/0
🔴	俊于线路	http://home.jundie.top:81/top98.json
🟡	橘子柚线路	https://mirror.ghproxy.com/https://raw.githubusercontent.com/hackyjso/box/main/jzy.txt
🟢	Qist线路	https://qist.ugigc.dpdns.org/jsm.json
🔴	潇洒备用接口	https://raw.githubusercontent.com/qist/tvbox/refs/heads/master/xiaosa/api.json
🟡	肥猫线路	http://肥猫.com/
🟢	肥猫备用1	http://hello.肥猫.com
🔴	肥猫备用2	https://6296.kstore.vip/facat.json
🟡	猫盒接口1	https://catbox.n13.club/jk/jsm.json
🟢	猫盒接口2	https://d.kstore.dev/download/12020/t4.json
🔴	小米线路3	http://miqk.cc/小米/DEMO.json
🟡	通用跳转接口	http://z.qiqiv.cn/123
🟢	Qist自用接口	https://github.moeyy.xyz/raw.githubusercontent.com/qist/tvbox/master/jsm.json
🔴	4KBox接口	http://tv.4kbox.top/api/api.json
🟡	宝盒接口	https://3043.kstore.space/bvhvip/bh/bh2.json
🟢	太极4K接口	https://gitee.com/yunfei-film-and-television_admin/taiji/raw/taiji/4K
🔴	挺好接口-1	http://ztha.top/TVBox/GYCK.json
🟡	挺好接口-2	http://ztha.top/TVBox/thdjk.json
🟢	霜辉月明PY接口	https://999740.xyz/raw.githubusercontent.com/lm317379829/PyramidStore/pyramid/py.json
🔴	七豪4K接口	http://38.165.20.168/柒豪4K.json
🟡	小程序多多仓库	https://framagit.org/xduo/cool/-/raw/main/小程序多多仓库.json
🟢	鸡你太美接口	https://700sjro44343.vicp.fun/eggp/qzku/tv.json
🔴	饭太硬主接口	http://www.饭太硬.top/tv/
🟡	OK杰克接口	https://jihulab.com/okcaptain/kko/raw/main/ok.txt
🟢	莫西莫西接口	http://ok.lfytv.cn/fm.json
🔴	直播接口汇总页	https://www.yiji007.com/user/share/NotesPage.aspx?data=WYH79nBcWQRnRN2XvbMiG7XCvWrS+Ar5
🟡	白嫖军团直播	http://gg.7749.org/z/0/白嫖军团.txt
📡 电视直播 / IPTV源

以下为各类电视直播源，包括国内、港澳台及娱乐直播等。
图标	名称	地址
🔴	长青直播源	http://yuan.haitangw.net/ZB/index.json
🟡	赛事直播	http://zhibo.feylen.top/fltv/viptv/viptv.php?tpye=.txt
🟢	拾光直播	https://slink.ltd/https://raw.githubusercontent.com/xmbjm/TV/refs/heads/master/output/user_result.txt
🔴	范明明直播	https://live.fanmingming.cn/tv/m3u/ipv6.m3u
🟡	Guovin直播	https://slink.ltd/https://raw.githubusercontent.com/Guovin/iptv-api/gd/output/result.m3u
🟢	大葱MyTV	https://tv.iill.top/m3u/MyTV
🔴	大葱Gather	https://tv.iill.top/m3u/Gather
🟡	大葱Live	https://tv.iill.top/m3u/Live
🟢	大葱Sport	https://tv.iill.top/m3u/Sport
🔴	天微直播	https://7337.kstore.space/twkj/tvzb.txt
🟡	开心直播	http://kxrj.site:55/lib/kx2024.txt
🟢	日后直播	http://rihou.cc:567/gggg.nzk
🔴	枫叶直播	https://gitee.com/fuscloud/android-cat-vod-spider/raw/master/json/tv.text
🟡	缝纫机直播	https://d.h6room.com/frjzb.txt
🟢	春盈天下直播	http://xhztv.top/cytx.txt
🔴	宝盒直播	https://mzjk.top/zb.txt
🟡	传说直播	http://kkk.jjjj.jiduo.me/user/tttt/api.txt
🟢	喵影视直播	http://meowtv.top/zb
🔴	虎芽一起看	https://live.freetv.top/huyayqk.m3u
🟡	抖渔一起看	https://live.freetv.top/douyuyqk.m3u
🟢	YY轮播	https://www.goodiptv.club/yylunbo.m3u?url=https://lunbo.freetv.top
🔴	活跃娱乐	https://www.goodiptv.club/bililive.m3u
🟡	长青直播2	http://yuan.haitang.net/ZB/index.json
🟢	小白直播	http://d.kstore.dev/download/11649/xiaobai1.txt
🔴	光直播源	https://vv.slink.ltd/cc/ZB/raw.txt
🟡	魏ivi直播	https://slink.ltd/https://raw.githubusercontent.com/Guovin/iptv-api/gd/output/result.m3u
🟢	微直播源	https://7337.kstore.space/twkj/tvzb.txt
🔴	盛天下直播	http://xhztv.top/cytjx.txt
🟡	影直播源	http://kkk.jiji.jiudo.me/user/ttttt/api.txt
🟢	年初三直播	https://5288.kstore.space/z.bmp
🔴	IPTV365直播	https://live.iptv365.org/live.txt
🟡	摸鱼直播源	http://go.work.gd/0/moyu.txt
🟢	金蛇直播源	https://pan.7so.top/f/l7G2tQ/金蛇.txt
🔴	XC直播源	https://fmbox.cc/php/xc.txt
🟡	520直播源	https://d.kstore.dev/download/2912/520.txt
🟢	Y977直播	http://api.y977.com/iptv.txt
🔴	盒子迷直播	http://盒子迷.top/ZB
🟡	长苏影视直播	https://gitee.com/wu-xuewei520/private/raw/master/JS/长苏影视.txt
🟢	电信直播源	http://go.work.gd/1/电信直播源.txt
🔴	元旦直播源	http://go.work.gd/1/一锅端直播_元旦.txt
🟡	苦短直播源	https://12428.kstore.space/苦短直播过年版.txt
🟢	央卫轮播简洁源	https://gitee.com/wjdjxjxj/tv/raw/master/qa.txt
🔴	猫影视直播	http://www.meowtv.top/mvzb.txt
🟡	轮播直播源	https://gitee.com/jin-xueling/ling1/raw/master/hu.txt
🟢	雨直播源	https://4key.cn/PP
🔴	DG直播源	http://101.200.122.188/dgzb.txt
🟡	歌直播源	http://1.gmbk.com/upload/62196219.txt
🟢	少儿接口	http://1.gmbk.com/upload/62476247.txt
🔴	测试接口	http://1.gmbk.com/upload/0713713.txt
🟡	龙直播源	https://gitee.com/lumiadragon/ysc/raw/main/zhibo.txt
🟢	热舞直播源	https://gitee.com/hot-song-and-hot-dance_0/live-streaming---tv-txt-direct/raw/master/m3u2.txt
🔴	WPYT直播源	http://wpyf.hk/tv/live/
🟡	仓库加速线路	https://cdn.jsdelivr.net/gh/yuanz177/IPTV@latest/live.m3u
🟢	YueChan-IPTV	https://mirror.ghproxy.com/https://raw.githubusercontent.com/YueChan/Live/main/IPTV.m3u
🔴	YanG-Gather	https://mirror.ghproxy.com/https://raw.githubusercontent.com/Yang-1989/m3u/main/Gather.m3u
🟡	Joevess-IPTV	https://mirror.ghproxy.com/raw.githubusercontent.com/joevessl/IPTV/main/home.m3u8
🟢	Kimentanm-IPTV	https://mirror.ghproxy.com/https://raw.githubusercontent.com/Kimentanm/aptv/master/m3u/iptv.m3u
🔴	Zbefine-IPTV	https://mirror.ghproxy.com/https://raw.githubusercontent.com/zbefine/iptv/main/iptv.m3u
🟡	茶客-IPTV	https://mirror.ghproxy.com/https://raw.githubusercontent.com/zbefine/iptv/main/iptv.txt
🟢	TVRadio	https://mirror.ghproxy.com/https://raw.githubusercontent.com/goolguy007/radioier/main/TVradio.m3u
🔴	暗黑EPG	https://epg.pw/test_channels.m3u
🟡	外网EPG	https://epg.pw/test_channels_banned_cn.m3u
🟢	EPG列表页	https://epg.pw/test_channel_page.html?lang=zh-hant
🔴	永久直播源	https://raw.githubusercontent.com/xiaozhang5656/xiaozhang-5656.github.io/main/iptv-live.txt
🟡	永久直播源2	http://www.lvyyttv.cn/yt/zhibo/1.txt
🟢	陪看直播源	https://live.freetv.top/huayayqk.m3u
🔴	陪看直播源2	https://live.freetv.top/douyuyqk.m3u
🟡	长苏2024直播	https://gitee.com/chen-dayi1/zhibo/raw/master/2024-9-192
🟢	港澳台终极版	https://www.kstore.space/download/2109/港澳台终极版.txt
外链网盘合集
1	大白™	https://pan.gt68.cn/
2	摆渡™	https://pan.baidu.re/
3	彩虹™	https://cccimg.com/
4	小黄人™	https://fel.forxhr.top:2022/
5	八九™	https://wp.sqsq.net/
6	惜染™	https://mpimg.cn/
7	云QQ™	https://pan.qqimm.cn/
8	蓝旅™	http://wp.lanlt.cn/
9	乐趣享™	https://www.lequxiang.com.cn/
10	松子云盘	https://pan.szfx.top/
11	资灵™	https://file.ziling.site/
12	无名IP™	http://114.132.198.144/
13	酷美网盘	https://www.kumeiwp.com/
14	逍遥网盘	http://file.cry33.com/
15	冰泰网盘	http://pan.aa53.cn/
16	凯速网盘⁺	https://my.ksust.com/kstore.htm
17	九七网盘⁺	https://www.97pan.cn/
18	小年网盘⁺	https://pan.jl8.top/
19	初心云盘⁺	https://chuxinya.top/
20	看见存储⁺	https://www.seeoss.com/
接口源第一季
一、🔴核心多仓接口🟡经典单仓接口🟢优质综合接口
🔴核心多仓

    https://xmbjm.github.io/ck.json（拾光）
    https://4708.kstore.space/ck.json（拾光）
    https://bitbucket.org/xduo/cool/raw/main/line.json
    https://cdn.jsdelivr.net/gh/yangxiaoge/tvbox_cust@master/tvbox/多仓.json
    https://tv. 蜗牛.top/4k.json（双仓）

🟡经典单仓

    http://tv.laohu.cool/tvbox.json（老虎单线）
    https://qixing.myhkw.com/DC.txt（天微精选仓 / 七星影仓）
    http://kxrj.site:55（开心服务器单仓）
    http://rihou.cc:55（日后服务器单仓）
    https://11256.kstore.space/免费勿传.json（七星影仓）

🟢优质综合

    https://gitee.com/yuan301/tv/raw/master/ok.json
    https://gitlab.com/lzc1021lzc/hjfggzs.hjys/-/raw/main/hjys.free.json
    https://gitee.com/lukei7/lib/raw/Luck/自建.json（蓝天 / Luck 自建）
    https://raw.liucn.cc/box/m.json（刘老备 / 老刘）
    https://jihulab.com/mengzhu2/ysc/-/raw/main/YSC.json（影视仓 Box）

二、🔴饭太硬专属线路🟡小米哥哥专属线路🟢欧歌（讴歌）专属线路
🔴饭太硬专属（主站 + 备用）

    http://www. 饭太硬.com/tv（主接口）
    http://www. 饭太硬.net/tv（备用 1）
    http://www. 饭太硬.xyz/tv（备用 2）
    http://fty.xxooo.cf/tv（备用 3）
    http://fty.888484.xyz/tv（备用 4）
    http://fty.333232.xyz/tv（备用 5）

🟡小米哥哥专属（主站 + 备用）

    https://mpanso.me/DEMO.json（主 1）
    https://tv.mpanso.me/DEMO.json（主 2）
    https://mi.mpanso.me/DEMO.json（主 3）
    http://www.mpanso.com/小米 / DEMO.json（主 4）
    https://3450.kstore.vip/DEMO.json（备用）

🟢欧歌（讴歌）专属（多仓 / 单线 / 多线）

    https://xn--yaay-rp5imh.v.nxog.top/api.php?id=1（多仓）
    https://xn--teet-rp5imh.v.nxog.top/api.php?id=2（多线路）
    https://xn--rxxr-rp5imh.v.nxog.top/api.php?id=3（单线路）
    https://xn--xggx-rp5imh.v.nxog.top/apitv.php?id=3（gx 线路）
    https://xn--tkh-mf3g9f.v.nxog.top/m/111.php?&J4m（tkh 线路）
    http://tv.nxog.top/api.php?mz=xb&id=1&b=欧歌（主接口）

三、🔴热门特色线路🟡经典老牌线路🟢新锐优质线路
🔴热门特色

    http://tvbox. 王二小放牛娃.top（王二小放牛娃）
    http:// 我不是。摸鱼儿.com（摸鱼主接口）
    http:// 肥猫.com/（肥猫主线路）
    http://ok321.top/ok（OK 猫公开接口）
    http://ok321.top/tv（OK 猫内部 / 开发接口）
    https://tv.youdu.fan:666（毒盒影视）
    https://100km.top/0（Ray / 骚零线路）

🟡经典老牌

    http://home.jundie.top:81/top98.json（俊佬 / 俊宇线路）
    https://ztha.top/TVBox/thdjk.json（挺好线路）
    https://weixine.net/ysc.json（运输车线路）
    http://meowtv.cn/tv（喵影视 / 喵影）
    https://fmbox.cc/（星辰 / 闪电优汐）
    http://cdn.qiaoji8.com/tvbox.json（巧记 / 巧技线路）

🟢新锐优质

    https://git.acwing.com/203BDXC/tvboxt/-/raw/main/CJ.json（超级接口）
    https://gitee.com/hailin886/fty/raw/master/tvbox/aishang.json（爱尚影视）
    https://git.acwing.com/shhentu/lzxw/-/raw/main/Monster.json（林中小屋 / 小屋）
    http://fmys.top/fmys.json（驸马）
    https://chuanshuo.77blog.cn/tv.json（传说线路）
    https://tv. 菜妮丝.top/（菜妮丝源）

四、🔴短剧专项接口🟡音乐戏曲接口🟢动漫直播接口
🔴短剧专项

    http://74.120.175.78/JK/XYQTVBox/dj.json（夜猫短剧）
    http://box.ufuzi.com/tv/qq/短剧频道 /api.json
    https://4708.kstore.space/DJ/DJ.json
    http://go2.work.gd/短剧
    https://gitea.moe/Fathers/EkfkgH/raw/branch/main/短剧.json

🟡音乐戏曲

    https://ddzb.fun/dgmusic/api.json（DG 音乐）
    http://101.200.122.188/xiqu（DG 戏曲）
    https://yyrj.fun/dc/（音乐台）

🟢动漫直播

    https://www.yingm.cc/dm/dm.json（动漫城源 / 动漫）
    https://gitdl.cn/https://raw.githubusercontent.com/PizazzGY/TVBox_warehouse/main/直播 /api.json（一直播）
    https://hb.xyyh.online/tvbox/（小虎斑・带弹幕）

五、🔴4K 超清专项🟡PG 专属接口🟢豆瓣评分推荐
🔴4K 超清专项

    http://38.165.20.168/柒豪 4K.json
    http://4K4K.shop/duo
    http://jk.baipiao4k.asia/（白嫖 4K）
    https://12448.kstore.space/Baipiao/tvbox/白嫖 4K.json（白嫖 4K 单线）
    https://gitee.com/yunfei-film-and-television_admin/taiji/raw/taiji/4K（太极☯️影视 4K）
    http://xhztv.top/4k.json（聚玩盒源 4K）

🟡PG 专属接口

    http://www.fish2018.ip-ddns.com/p/jsm.json（PG 在线）
    http://ttkx.cc:55/pg/jsm.json（天天开心 PG 包）
    http://data.mxlgsl.cn/data/pg/jsm.json（在线 PG 包）
    https://git.acwing.com/iduoduo/orange/-/raw/main/jsm.json（Pg 接口）
    http://ygbhbox.3vfree.club/pg/jsm.json（宝盒没宝 PG）

🟢豆瓣评分推荐

    http://175.178.251.183:6689/tv.txt（豆瓣评分 / 懒人单线）
    http://39.101.135.137:8080/（豆瓣小白龙）
    https://yydf.540734621.xyz/QQ/yydf2024.json（豆瓣 Q 群版）

六、🔴备用兜底接口🟡服务器单仓 / 单线🟢小众优质接口
🔴备用兜底

    https://9877.kstore.space/FourDS/api.json（多线路接口）
    https://9877.kstore.space/FourD/api.json（单线路接口）
    https://6296.kstore.vip/facat.json（肥猫备用源）
    http://39.101.135.137:8888（浪里小白龙备用）
    http://39.101.135.137:8686（浪里小白龙多仓）
    https://d.kstore.dev/download/9280/wex.json（王二小防屏蔽）

🟡服务器单仓 / 单线

    http://ttkx.cc:55/天天开心（开心服务器单线）
    http://rihou.cc:55/天天开心（日后服务器单线）
    https://7337.kstore.space/twvip/自用测试.json（天微单线）
    https://qixing.myhkw.com/自用测试勿传 DC.txt（天微单仓）

🟢小众优质

    https://gitee.com/Tangxg2017/dc/raw/master/tangxgDC-20240829.json（糖小果）
    https://jihulab.com/jyqhkd1/jk/-/raw/main/8.json（凯弟多仓）
    https://gitlab.com/dokiss/tvbox/-/raw/main/圥忈.json（多多应用 / 多多影音）
    https://gitee.com/blssss/jk/raw/api/bls.json（玩偶软件）
    https://raw.bgithub.xyz/hanhan8127/TVBox/main/hanXC.json（胜寒）
    https://2912.kstore.space/0506.json（西夏）

接口源第二季
一、单仓接口

    🔴匿名单仓：https://12586.kstore.space/123.txt
    🟡天微单仓：https://qixing.myhkw.com/DC.txt
    🟢潇洒单仓：https://9877.kstore.space/AnotherD/api.json
    🔴欧歌单仓：https://xn--anna-wn6lw489o.v.nxog.top/nxog/oua.php
    🟡关羽单仓①：https://4708.kstore.space/box/svip.json
    🟢关羽单仓②：https://4708.kstore.space/svip/svip.json

二、多仓接口

    🔴匿名多仓：https://12586.kstore.space/123.json
    🟡潇洒多仓：https://9877.kstore.space/AnotherDS/api.json
    🟢多仓汇总①：https://4708.kstore.space/ck.json
    🔴多仓汇总②：https://xmbjm.github.io/ck.json
    🟡多仓汇总③：http://tv.nxog.top/api.php?id=1
    🟢多仓汇总④：https://github.moeyy.xyz/https://raw.githubusercontent.com/xmbjm/xmbjm.github.io/main/ck.json
    🔴关羽多仓：https://gitlab.com/xmbjm/omg/raw/main/api.json
    🟡影视多仓：https://raw.gitmirror.com/PizazzGY/TVBox/main/api.json

三、直播源订阅

    🔴直播源①：https://sub.ottiptv.cc/iptv.m3u
    🟡直播源②：https://sub.ottiptv.cc/huyayqk.m3u
    🟢直播源③：https://sub.ottiptv.cc/douyuyqk.m3u
    🔴直播源④：https://sub.ottiptv.cc/yylunbo.m3u
    🟡直播源⑤：https://sub.ottiptv.cc/bililive.m3u
    🟢酷 9 直播源：http://47.120.41.246:8899/zb.txt
    🔴TV 直播源：http://is.is-great.org/i/1774438.txt
    🟡澜露直播源：https://15530.kstore.space/diyi/dagai

四、4K / 高清点播接口

    🔴4K 点播①：http://v-dragon.com.hk/4k/
    🟡4K 点播②：http://tv.4kbox.top/4k/index.php
    🟢茴香 4K 点播：https://12523.kstore.space/hx.json
    🔴流年点播：http://210.245.166.68:1188/tvbox/liunian/
    🟡澜露点播：https://15530.kstore.space/diyi/dianbo
    🟢幸福年年点播：http:// 年年幸福.icu/ 蓝天白云 / 蓝天白云.json
    🔴神器点播：https:// 神器每日推送.tk/pz.json

五、专项线路（热门博主 / 工具）

    🔴饭太硬①：http:// 饭太硬.com/tv
    🟡饭太硬②：http://www. 饭太硬.com/tv
    🟢饭太硬③：http://www. 饭太硬.net/tv
    🔴饭太硬④：http://www. 饭太硬.xyz/tv
    🟡饭太硬⑤：http://fty.xxooo.cf/tv
    🟢饭太硬⑥：http://www. 饭太硬.top/tv/
    🔴肥猫①：http:// 肥猫.com/
    🟡肥猫②：http://hello. 肥猫.com
    🟢肥猫③：https://6296.kstore.vip/facat.json
    🔴摸鱼线路：http:// 我不是。摸鱼儿.top
    🟡王二小①：http://tvbox. 王二小放牛娃.top
    🟢王二小②：http://tvbox. 王二小放牛娃.xyz
    🔴OK 接口①：http://ok321.top/ok
    🟡OK 接口②：http://ok321.top/tv
    🟢巧技接口①：http://cdn.qiaoji8.com/tvbox.json
    🔴巧技接口②：http://pandown.pro/tvbox/tvbox.json
    🟡小米线路①：http://miqk.cc/小米 / DEMO.json
    🟢小米线路②：http://www.mpanso.com/小米 / DEMO.json
    🔴小米线路③：https://mpanso.me/DEMO.json
    🟡小虎斑线路：http://hb. 小虎斑.site:25252 / 仅供测试
    🟢小虎线路：https://hb.xyyh.online/tvbox/

六、备用 / 特色接口

    🔴南风①：https://gh-proxy.com/https://raw.githubusercontent.com/yoursmile66/TVBox/refs/heads/main/XC.json
    🟡南风②：https://github.moeyy.xyz/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json
    🟢香雅情线路：https://gh-proxy.com/https://raw.githubusercontent.com/xyq254245/xyqonlinerule/main/XYQTVBox.json
    🔴少儿线路：https://jihulab.com/ymz1231/xymz/-/raw/main/ymshaoer
    🟡如意接口：https://gitee.com/wynp/ys/raw/master/yc.json
    🟢有毒接口：https://tv.youdu.fan:666
    🔴毒盒接口：https://tv.youdu.fan:666/毒盒影视 /
    🟡菜妮接口①：https://tv.xn--yhqu5zs87a.top
    🟢菜妮接口②：https://tv. 菜妮丝.top
    🔴刘云接口：https://git.acwing.com/999/tvbox/raw/main/影视.json
    🟡愿望接口：https://gh-proxy.com/raw.githubusercontent.com/yuanwangokk-1/TV-BOX/main/drpys/jsm.json
    🟢刀客接口：https://gitlab.com/dokiss1/tvbox/-/raw/master/doki-ST.json

七、荷城茶秀专属接口

    🔴荷城①：http://rihou.cc:88/荷城茶秀
    🟡荷城②：http://rihou.vip:88/荷城茶秀
    🟢荷城③：https://jihulab.com/z-blog/xh2/raw/main/t.json
    🔴荷城④：https://jihulab.com/z-blog/vip/raw/main/xpg/t.json

八、小说资源接口

    🔴小说接口汇总：https://www.yckceo.com/yuedu/shuyuans/json/id/111.json

接口源第三季
🎯 核心基础接口
一、核心经典接口（高频维护・稳定可用）

🔴饭太硬：http://www. 饭太硬.com/tv

🟡小米哥哥：https://mpanso.me/DEMO.json

🟢王二小放牛娃：http://tvbox. 王二小放牛娃.top

🔴摸鱼：http://我不是.摸鱼儿.com

🟡讴歌：https://xn--tkh-mf3g9f.v.nxog.top/m/111.php

🟢OK 猫：http://ok321.top/ok

🔴肥猫：http:// 肥猫.com/

🟡俊佬：http://home.jundie.top:81/top98.json

🟢宝盒：http://mzjk.top/禁止贩卖
二、4K 超清专属接口（超高清画质）

🔴柒豪 4K：http://38.165.20.168/柒豪4K.json

🟡青龙 4K：https://gitee.com/yiwu369/6758/raw/master/青龙/2.json

🟢蜗牛 4K：https://4k.蜗牛.top/4k.json

🔴聚玩盒 4K：http://xhztv.top/4k.json

🟡白嫖 4K：http://jk.baipiao4k.asia/

🟢幸福年年 4K：https://11405.kstore.space/xiaye/qk4k.json
三、通用优质接口（高适配・日常常用）

🔴青龙 1080：https://gitee.com/yiwu369/6758/raw/master/青龙/1.json

🟡白虎：https://gitee.com/yiwu369/6758/raw/master/白虎/白虎.json

🟢南风：https://gh-proxy.com/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json

🔴超级接口：https://git.acwing.com/203BDXC/tvboxt/-/raw/main/CJ.json

🟡星辰：https://fmbox.cc/

🟢喵影视：http://meowtv.cn/tv

🔴潇洒：https://github.moeyy.xyz/https://raw.githubusercontent.com/PizazzGY/TVBox/main/api.json

🟡菜妮丝：https://tv.菜妮丝.top

🟢挺好：https://ztha.top/TVBox/thdjk.json

🔴传说：https://chuanshuo.77blog.cn/tv.json

🟡蓝天自建：https://gitee.com/lukei7/lib/raw/Luck/自建.json

🟢驸马：http://fmys.top/fmys.json
四、高清通用接口（1080P・免扫追剧）

🔴幸福年年 1080：https://11405.kstore.space/xiaye/1080.json

🟡幸福年年 4K 高清：https://11405.kstore.space/xiaye/4k1.json

🟢小脑斧：https://6492.kstore.space/xnf/xnf.json
📦 聚合拓展接口
一、多仓聚合接口（多源整合・一站通看）

🔴拾光多仓：https://xmbjm.github.io/ck.json

🟡匿名多仓：https://12586.kstore.space/123.json

🟢金鹰多仓：http://530.my3v.work/f.json

🔴蓝色影视多仓：https://d.kstore.dev/download/4684/Xboxb.json

🟡通用多仓：https://4708.kstore.space/ck.json

🟢凯弟多仓：https://jihulab.com/jyqhkd1/jk/-/raw/main/8.json

🔴酷系多仓：https://bitbucket.org/xduo/cool/raw/main/line.json

🟡蜗牛多仓：https://tv. 蜗牛.top/DC.txt
二、多仓 / 综合接口（全场景适配）

🔴自用测试接口：https://7337.kstore.space/kjtv/自用测试.json

🟡NB666 接口：https://try.gogs.io/NB666/api/raw/main/config.bin

🟢老虎接口：http://tv.laohu.cool/tvbox.json

🔴OK 接口：https://gitee.com/yuan301/tv/raw/master/ok.json

🟡免费接口：https://gitlab.com/lzc1021lzc/hjfggzs.hjys/-/raw/main/hjys.free.json

🟢Qist 接口：https://ghfast.top/https://raw.githubusercontent.com/qist/tvbox/refs/heads/master/jsm.json

🔴年年有余接口：https://d.kstore.dev/download/4684/年年有余 /gfdc.json

🟡自主云接口：http://zizhuyun.top/yuan/zizhuyun.json

🟢分享者接口：https://github.moeyy.xyz/https://raw.githubusercontent.com/maoystv/6/main/000.json

🔴小米接口：http://www.mitvbox.xyz/小米 / DEMO.json

🟡多多仓库接口：https://framagit.org/xduo/cool/-/raw/main/room.json

🟢神州在线 2025：https://gitee.com/yiwu369/6758/raw/master/2025.json

🔴神州在线 2024：https://gitee.com/yiwu369/6758/raw/master/2024.json

🟡青龙接口：https://gitee.com/yiwu369/6758/raw/master/青龙 / 1.json

🟢宝盒接口：https://3043.kstore.space/bhvip/bh/bh2.json

🔴小程序多多仓库：https://framagit.org/xduo/cool/-/raw/main/小程序多多仓库.json

🟡茄子库接口：https://700sjro44343.vicp.fun/eggp/qzku/tv.json

🟢多仓接口：https://4708.kstore.space/ck.json

🔴XMBJM 接口：https://xmbjm.github.io/ck.json

🟡多线路接口：http://tv.nxog.top/api.php?id=1

🟢XMBJM 仓库接口：https://github.moeyy.xyz/https://raw.githubusercontent.com/xmbjm/xmbjm.github.io/main/ck.json

🔴关羽 SVIP 接口：https://4708.kstore.space/box/svip.json

🟡关羽 SVIP2 接口：https://4708.kstore.space/svip/svip.json

🟢关羽 API 接口：https://gitlab.com/xmbjm/omg/raw/main/api.json

🔴PizazzGY 接口：https://raw.gitmirror.com/PizazzGY/TVBox/main/api.json

🟡无敌凯少爷躺平单仓：https://git.acwing.com/SVIP/007/-/raw/main/无敌凯少爷躺平单仓接口🈲止贩卖，举报贩卖有奖.json

🟢讴歌接口：https://xn--56jc783u8uaj9fd4ae3g5r7adg8d.v.nxog.top/api.php?id=1

🔴小米接口 2：http://miqk.cc/小米 / DEMO.json

🟡短网址接口：http://z.qiqiv.cn/123

🟢小虎斑测试接口：http://hb. 小虎斑.site:25252 / 仅供测试

🔴666 接口 1：https://gitee.com/kgysp/tv/raw/box/666.api

🟡666 接口 2：https://raw.gitmirror.com/kgsp/tv/box/666.api

🟢666 接口 3：https://git.acwing.com/kgsp/tv/raw/box/666.json

🔴666 接口 4：https://ghproxy.net/https://raw.githubusercontent.com/kgsp/tv/box/666.json

🟡666 接口 5：https://gitlab.com/kgys/tv/raw/box/666.api

🟢666 接口 6：https://jihulab.com/kgsp/tv/raw/box/666.json

🔴多仓配置接口：https://cdn.jsdelivr.net/gh/yangxiaoge/tvbox_cust@master/tvbox/多仓.json

🟡测试接口：https://gh-proxy.com/https://raw.githubusercontent.com/ls125781003/testboxapi/main/tvbox/api.json

🟢南风接口 2：https://agit.ai/Yoursmile7/TVBox/raw/branch/master/XC.json

🔴神器接口：https:// 神器每日推送.tk/pz.json

🟡巧技接口：http://pandown.pro/tvbox/tvbox.json

🟢Ray 接口：https://100km.top/0

🔴橘子柚接口：https://mirror.ghproxy.com/https://raw.githubusercontent.com/hackyjso/box/main/jzy.txt

🟡电视自用接口：https://github.moeyy.xyz/raw.githubusercontent.com/qist/tvbox/master/jsm.json

🟢潇洒接口：https://raw.githubusercontent.com/qist/tvbox/refs/heads/master/xiaosa/api.json

🔴潇洒接口 2：https://qist.ugigc.dpdns.org/xiaosa/api.json

🟡刀客接口：https://gitlab.com/dokiss1/tvbox/-/raw/master/doki-ST.json

🟢短文接口 1：http://dxawi.github.io/0/0.json

🔴短文接口 2：https://xhdwc.tk/0

🟡运输接口 1：https://weixine.net/ysc.json

🟢运输接口 2：https://cf.weixine.net/ysc.json

🔴运输接口 3：http://svip.weixine.net:88/uploads/itvbox/svip.json

🟡荷城茶秀 1：http://rihou.cc:88/荷城茶秀

🟢荷城茶秀 2：http://rihou.vip:88/荷城茶秀

🔴Z-Blog 接口 1：https://jihulab.com/z-blog/xh2/raw/main/t.json

🟡Z-Blog 接口 2：https://jihulab.com/z-blog/vip/raw/main/xpg/t.json

🟢猫影接口 2：https://www.macms.pro/box/3.json

🔴评估接口 1：https://raw.gitmirror.com/gaotianliuyun/gao/master/0825.json

🟡评估接口 2：https://ghproxy.net/raw.githubusercontent.com/gaotianliuyun/gao/master/0825.json

🟢俊宇接口 1：https://raw.gitmirror.com/gaotianliuyun/gao/master/js.json

🔴俊宇接口 2：https://ghproxy.net/raw.githubusercontent.com/gaotianliuyun/gao/master/js.json

🟡俊宇接口 3：https://github.moeyy.xyz/https://raw.githubusercontent.com/gaotianliuyun/gao/master/js.json

🟢香雅接口 1：https://raw.gitmirror.com/gaotianliuyun/gao/master/XYQ.json

🔴香雅接口 2：https://github.moeyy.xyz/https://raw.githubusercontent.com/gaotianliuyun/gao/master/XYQ.json

🟡道长接口：https://pastebin.com/raw/5NHaxyGR

🟢道长接口 2：http://yuhuahx.com/hx/道长 /d

🔴刘云接口：https://git.acwing.com/999/tvbox/raw/main/影视.json

🟡愿望接口：https://gh-proxy.com/raw.githubusercontent.com/yuanwangokk-1/TV-BOX/main/drpys/jsm.json

🟢心魔接口：https://gh-proxy.com/raw.githubusercontent.com/yw88075/tvbox/main/yw.json
三、影视资源 / 4K 高清补充

🔴4K 秒播接口：http://154.12.37.204:8089/hebing

🟡太极影视 4K：https://gitee.com/yunfei-film-and-television_admin/taiji/raw/taiji/4K

🟢挺好接口 GYCK：http://ztha.top/TVBox/GYCK.json

🔴某位大佬接口：http://tv.4kbox.top/api/api.json

🟡综合接口：http://nn.qi-simple.top/common.json

🟢网盘接口：http://nn.qi-simple.top/cloud.json

🔴蓝光接口：http://nn.qi-simple.top/film.json

🟡幸福年年备用：http://ok.lfytv.cn/fm.json

🟢Jason 接口 1：https://gh.jasonzeng.dev/https://raw.githubusercontent.com/2124662895/yydhj/mainvhh/2023ususiua.php

🔴Jason 接口 2：https://gh.jasonzeng.dev/https://raw.githubusercontent.com/2124662895/yydhj/mainvhh/xbrthx.json

🟡小米线路：http://www.mpanso.com/小米 / DEMO.json

🟢小米线路 2：http://xhww.fun/小米 / DEMO.json

🔴小米线路 3：https://mpanso.me/DEMO.json

🟡潇洒接口 3：https://9877.kstore.space/AnotherD/api.json

🟢毒盒影视 2：https://tv.youdu.fan:666/毒盒影视 /

🔴菜妮丝接口 2：https://tv.xn--yhqu5zs87a.top

🟡巧记接口 1：http://cdn.qiaoji8.com/tvbox.json

🟢巧记接口 2：http://pandown.pro/tvbox/tvbox.json

🔴饭太硬接口 1：http:// 饭太硬.com/tv

🟡饭太硬接口 2：http://www. 饭太硬.top/tv/

🟢饭太硬备用 1：http://www. 饭太硬.net/tv

🔴饭太硬备用 2：http://www. 饭太硬.xyz/tv

🟡饭太硬备用 3：http://fty.xxooo.cf/tv

🟢王二小放牛娃 2：http://tvbox. 王二小放牛娃.xyz

🔴摸鱼接口 1：http:// 我不是。摸鱼儿.top

🟡霜辉月明接口：https://999740.xyz/raw.githubusercontent.com/lm317379829/PyramidStore/pyramid/py.json

🟢肥猫备用 1：http://hello. 肥猫.com

🔴肥猫备用 2：https://6296.kstore.vip/facat.json

🟡OK 杰克接口：https://jihulab.com/okcaptain/kko/raw/main/ok.txt

🟢小虎接口：https://hb.xyyh.online/tvbox/

🔴南风接口 1：https://github.moeyy.xyz/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json

🟡南风接口 3：https://ghproxy.net/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json

🟢南风接口 4：https://jihulab.com/Yoursmile/TVbox/raw/master/Yoursmile.jar

🔴高天流云接口 1：https://raw.gitmirror.com/gaotianliuyun/gao/master/0826.json

🟡高天流云接口 2：https://ghproxy.net/raw.githubusercontent.com/gaotianliuyun/gao/master/0826.json

🟢高天流云接口 3：https://github.moeyy.xyz/https://raw.githubusercontent.com/yoursmile66/TVBox/main/XC.json
🎭 专项特色接口
一、短剧专项

🔴夜猫短剧：http://74.120.175.78/JK/XYQTVBox/dj.json

🟡Ufuzi 短剧：http://box.ufuzi.com/tv/qq/短剧频道 /api.json

🟢拾光短剧：https://4708.kstore.space/DJ/DJ.json
二、音乐 / 戏曲 / 电台

🔴DG 音乐：https://ddzb.fun/dgmusic/api.json

🟡DG 戏曲：http://101.200.122.188/xiqu

🟢音乐台接口：https://ddzb.fun/dgmusic/api.json

🔴戏曲直播：http://l.gmbbk.com/upload/0713713.txt

🟡DG 直播源（戏曲）：http://101.200.122.188/dgzb.txt
三、动漫专项

🔴动漫城：https://www.yingm.cc/dm/dm.json
🚨 备用兜底接口

🔴懒人单线：http://175.178.251.183:6689/tv.txt

🟡老虎单线：http://tv.laohu.cool/tvbox.json

🟢天微科技：https://qixing.myhkw.com/DC.txt

🔴毒盒影视：https://tv.youdu.fan:666

🟡五月天：https://cccimg.com/down.php/33c22b45fa8db8a828af2077b92b8cb7.json

🟢糖小果：https://gitee.com/Tangxg2017/dc/raw/master/tangxgDC-20240829.json

🔴小苹果：https://bitbucket.org/xduo/duoapi/raw/master/xpg.json

🟡大虾：https://dxawi.github.io/0/0.json

🟢老刘（老刘备）：https://raw.liucn.cc/box/m.json

🔴肥猫备用：https://6296.kstore.vip/facat.json

🟡饭太硬备用：http://www. 饭太硬.net/tv

🟢小米备用：https://3450.kstore.vip/DEMO.json
🛠️ 工具辅助接口
一、视频链接解析

🔴爱豆儿解析：https://jx.aidouer.net/?url=

🟡战狼部解析：https://jx.zhanlangbu.com/?url=

🟢联发卡解析：https://vip.lianfaka.com/vip/?url=

🔴博兹解析：https://jx.bozrc.com:4433/player/?url=
二、PG 包（配套使用）

🔴天天开心 PG：http://ttkx.cc:55/pg/jsm.json

🟡多多 PG：https://git.acwing.com/iduoduo/orange/-/raw/main/jsm.json

🟢宝盒没宝 PG：http://ygbhbox.3vfree.club/pg/jsm.json
三、评分推荐（优质片单）

🔴豆瓣评分：http://175.178.251.183:6689/tv.txt

🟡豆瓣 Q 群版：https://yydf.540734621.xyz/QQ/yydf2024.json
```
 9. 羊壳peekpili使用教程（别人整理）
 ---
 ```shell
 软件下载地址:
https://pan.quark.cn/s/8fc2489169b6
【在线文档】PeekPili基本使用方法及道长包下载和TNDB配置
https://docs.qq.com/doc/DR2FFV2N0UXNadUZz
【在线文档】Peek手机本地包使用方法
https://docs.qq.com/doc/DR0NHQ1JkVnZERk5k
【在线文档】Peek电脑本地包使用方法
https://docs.qq.com/doc/DR0pqRkNVY3NpSUth
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
//你的tvbox api json格式
//https://github.com/qist/tvbox 项目对应的json数据，请检测是否存在多余“{}”
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
![image-20260729154524486](./images/image-20260729154524486.png)



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

![image-20260729154958106](./images/image-20260729154958106.png)

![image-20260729155016999](./images/image-20260729155016999.png)

![image-20260729155038000](./images/image-20260729155038000.png)

![image-20260729155111250](./images/image-20260729155111250.png)

![image-20260729155132980](./images/image-20260729155132980.png)

![image-20260729155145136](./images/image-20260729155145136.png)

![image-20260729161953211](./images/image-20260729161953211.png)



![image-20260729162115788](./images/image-20260729162115788.png)

# 域名配置

---



![image-20260729162207807](./images/image-20260729162207807.png)

![image-20260729162648407](./images/image-20260729162648407.png)

![image-20260729162714485](./images/image-20260729162714485.png)



![image-20260729162446356](./images/image-20260729162446356.png)



# 自定义cloudflareAPI令牌

---



![image-20260729161705815](./images/image-20260729161705815.png)



![image-20260729161509605](./images/image-20260729161509605.png)

![image-20260729161533207](./images/image-20260729161533207.png)

![image-20260729161556113](./images/image-20260729161556113.png)

# 域名托管到cloudflare

---



![image-20260729163155136](./images/image-20260729163155136.png)

![image-20260729163217144](./images/image-20260729163217144.png)

![image-20260729163114684](./images/image-20260729163114684.png)

## 域名配置dns

![image-20260729163309453](./images/image-20260729163309453.png)

## 域名注册商配置cloudflare的dns

> carioca.ns.cloudflare.com
>
> jermaine.ns.cloudflare.com

![image-20260729163451507](./images/image-20260729163451507.png)

![image-20260729163018773](./images/image-20260729163018773.png)
