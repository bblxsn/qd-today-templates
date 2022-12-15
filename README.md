# 公共模板库 <sub>For Qiandao 签到框架</sub>

![GitHub last commit](https://img.shields.io/github/last-commit/qiandao-today/templates.svg?style=popout-square)

## 🏠简介

> 项目基于开源的签到框架站使用, 发布者在此发布模板仅供示范, 使用公共模板产生的任何问题需自行承担!

- [binux/qiandao](https://github.com/binux/qiandao) 最初版本框架，已停止维护。

- [qiandao-today/qiandao](https://github.com/qiandao-today/qiandao)  最新版框架，现持续更新中。

- 现模板基于 [最新版框架](https://github.com/qiandao-today/qiandao) 使用, 具体使用方式请自行学习。

> 极个别模板不兼容 [旧版本](https://github.com/binux/qiandao) 框架, 如有不兼容请使用 [最新版](https://github.com/qiandao-today/qiandao) 。
>
> 仅20211228及之后版本签到框架支持`api://`请求, 其他版本使用模板时请自行升级签到框架 或 将`api://`更换为`http://localhost/`

## 💭交流反馈

> QQ群: [642842749](https://jq.qq.com/?_wv=1027&k=PXZcLlO1) | **仅用于模板交流及BUG提交反馈**

## 🏁网站

Tips:

1. 链接里最好使用 `raw.githubusercontent.com` 的模板地址，其他的链接没有测试过
2. 修改日期格式 `四位年-两位月-两位日 24小时:两位分:两位秒` ，例子：`2020-05-15 07:03:47`

| 网站 | 作者 | 链接 | 修改日期 | 备注/日志 |
| --- | --- | --- | --- | --- |
| 189天翼云盘-账号版 | [gxitm](https://github.com/gxitm) <br> [a76yyyy](https://github.com/a76yyyy) <br> [wjf0214](https://github.com/wjf0214) | [189天翼云盘-账号版.har](https://raw.githubusercontent.com/qiandao-today/templates/master/189天翼云盘-账号版.har) | 2021-12-24 20:30:00 | 用户名+密码<br>用户名为手机号<br><https://cloud.189.cn/> |
| 国航APP | [AragonSnow](https://github.com/AragonSnow) | [airchina.har](https://raw.githubusercontent.com/qiandao-today/templates/master/airchina.har) | 2020-06-17 02:40:10 | 抓包，app杀台后不用输密码登录就行，这两个链接里有这个参数<br>前两个在<br><https://m.airchina.com.cn:9061/worklight/apps/services/api/AirChina/iphone/init> <br> param在 <br> <https://m.airchina.com.cn:9061/worklight/apps/services/api/AirChina/iphone/query> <br> paramters=到&结束<br>20200617更新：替换公共API地址，改用内置，需要配合aragonsonw/qiandao最新版使用 |
| 轻之国度 | [AragonSnow](https://github.com/AragonSnow) | [lightnovel 轻之国度.har](https://raw.githubusercontent.com/qiandao-today/templates/master/lightnovel%20%E8%BD%BB%E4%B9%8B%E5%9B%BD%E5%BA%A6.har) | 2020-05-20 15:43:45 | cks 网页cookie<br><https://www.lightnovel.us/> |
| 精易论坛 | [wjf0214](https://github.com/wjf0214) | [精易论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/精易论坛.har) | 2021-09-28 17:00:00 | cookie<br><https://bbs.125.la> |
| 腾讯视频VIP | [devil](https://github.com/q123458384) | [腾讯视频VIP.har](https://raw.githubusercontent.com/qiandao-today/templates/master/腾讯视频VIP.har) | 2020-05-25 14:11:06 | cookie<br>腾讯视频手机APP抓包cookie |
| 柠檬PT签到 | [devil](https://github.com/q123458384) | [柠檬PT签到.har](https://raw.githubusercontent.com/qiandao-today/templates/master/leaguehd%E6%9F%A0%E6%AA%ACPT.har) | 2020-05-25 14:06:23 | cookie<br><https://leaguehd.com/attendance.php> |
| 网易云音乐-电脑 AND 手机 | [qiandao.today公共模板](https://qiandao.today/tpls/public) | [网易云音乐-电脑 AND 手机.har](https://raw.githubusercontent.com/qiandao-today/templates/master/%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90-%E7%94%B5%E8%84%91%20AND%20%E6%89%8B%E6%9C%BA.har) | 2020-06-25 21:12:03 | cookie<br><https://music.163.com/> |
| summer-plus(原south-plus) | [AragonSnow](https://github.com/AragonSnow) <br> [github-h](https://github.com/github-h)  | [summer-plus(原south-plus).har](https://raw.githubusercontent.com/qiandao-today/templates/master/summer-plus(%E5%8E%9Fsouth-plus).har) | 2021-02-13 16:00:00 | cookie<br><https://www.summer-plus.net/> |
| ZodGame论坛 | [github-h](https://github.com/github-h) | [ZodGame论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/ZodGame论坛.har) | 2021-02-13 16:00:00 | cookie<br>若无法正常访问，国内vps请自行添加hosts文件<br><https://zodgame.xyz> |
| 星空论坛seikuu | [github-h](https://github.com/github-h) | [星空论坛seikuu.har](https://raw.githubusercontent.com/qiandao-today/templates/master/星空论坛seikuu.har) | 2021-02-13 16:00:00 | cookie<br><https://bbs2.seikuu.com/> |
| 终点论坛 | [FellBan](https://github.com/FellBan) | [终点论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/终点论坛.har) | 2021-12-24 20:30:00 | cookie<br><https://bbs.zdfx.net/> |
| 哥特动漫王国 | [github-h](https://github.com/github-h) | [哥特动漫王国.har](https://raw.githubusercontent.com/qiandao-today/templates/master/哥特动漫王国.har) | 2021-12-09 16:00:00 | cookie<br>论坛已经恢复，该模板带vip自动领取奖励，非vip用户也可以正常使用<br><https://www.gtloli.gay/forum.php/> |
| 萌出血动漫论坛 | [github-h](https://github.com/github-h) | [萌出血动漫论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/萌出血动漫论坛.har) | 2021-12-09 16:00:00 | cookie<br><https://www.bbsmcx.com/forum.php> |
| 好快的车车(原HMOE俱乐部) | [github-h](https://github.com/github-h) | [好快的车车.har](https://raw.githubusercontent.com/qiandao-today/templates/master/好快的车车.har) | 2021-07-12 16:00:00 | 用户名+密码<br><https://cheche.one/> |
| 花火学园 |  [wjf0214](https://github.com/wjf0214) | [花火学园.har](https://raw.githubusercontent.com/qiandao-today/templates/master/花火学园.har) | 2022-03-02 21:00:00 | username:账号<br>password:密码<br><https://www.sayhuahuo.com/> |
| 夏跡natsunokiseki | [github-h](https://github.com/github-h) | [夏跡natsunokiseki.har](https://raw.githubusercontent.com/qiandao-today/templates/master/夏跡natsunokiseki.har) | 2021-02-13 16:00:00 | 用户名+密码<br>每日登录奖励<br>该论坛时不时会忘记续费主机导致任务失败<br><https://bbs.natsunokiseki.org/> |
| 萌幻之乡 | [wjf0214](https://github.com/wjf0214)  | [萌幻之乡.har](https://raw.githubusercontent.com/qiandao-today/templates/master/萌幻之乡.har) | 2022-07-17 20:20:00 | username:账号<br>password:密码<br>自定义UA:可选,空为默认UA<br>签到+点赞x4<br><https://www.hmoe11.net/> |
| KDays论坛 |  [wjf0214](https://github.com/wjf0214)  | [KDays论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/KDays论坛.har) | 2021-11-20 21:20:00 |  username:账号<br>password:密码<br><https://bbs.kdays.net/> |
| 吾爱破解 | [wjf0214](https://github.com/wjf0214) | [吾爱破解.har](https://raw.githubusercontent.com/qiandao-today/templates/master/吾爱破解.har) | 2022-05-05 23:30:00 | 登录后首页cookie,f12的时候请选中复制,不要右键复制值。<br>国内vps供应商已经被加ACL黑名单，请使用家庭IP<br><https://www.52pojie.cn/> |
| ArcTime字幕平台 | [github-h](https://github.com/github-h) | [ArcTime字幕平台.har](https://raw.githubusercontent.com/qiandao-today/templates/master/ArcTime字幕平台.har) | 2021-02-13 16:00:00 | 用户名+密码<br><https://m.arctime.cn/> |
| 柚坛社区 | [github-h](https://github.com/github-h) | [柚坛社区.har](https://raw.githubusercontent.com/qiandao-today/templates/master/柚坛社区.har) | 2021-12-09 16:00:00 | cookie<br>每日登录奖励<br><https://uotan.cn/> |
| keylol(原SteamCN蒸汽论坛) | [github-h](https://github.com/github-h) | [keylol(原SteamCN蒸汽论坛).har](https://raw.githubusercontent.com/qiandao-today/templates/master/keylol(原SteamCN蒸汽论坛).har) | 2021-02-13 16:00:00 | cookie<br><https://keylol.com/> |
| 3DMGAME论坛 | [github-h](https://github.com/github-h) | [3DMGAME论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/3DMGAME论坛.har) | 2021-12-09 16:00:00 | cookie<br>部分日常任务会随等级发生更改，有能力的可以自行修改<br><https://bbs.3dmgame.com/> |
| QQNTR论坛 | [github-h](https://github.com/github-h) | [QQNTR论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/QQNTR论坛.har) | 2021-02-13 16:00:00 | cookie<br><https://iya.app/> |
| CSDN-专业IT技术论坛 | [github-h](https://github.com/github-h) | [CSDN-专业IT技术论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/CSDN-专业IT技术论坛.har) | 2021-02-13 16:00:00 | 用户名+cookie<br>此为签到模块，记得定期抽奖<br><https://www.csdn.net/> |
| 杉果 | [github-h](https://github.com/github-h) <br> [wjf0214](https://github.com/wjf0214) | [杉果.har](https://raw.githubusercontent.com/qiandao-today/templates/master/杉果.har) | 2021-09-16 10:00:00 | 用户名+密码<br>用户名为邮箱<br><https://sonkwo.com/> |
| 华盟论坛 | [github-h](https://github.com/github-h) | [华盟论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/华盟论坛.har) | 2021-02-13 16:00:00 | 用户名+密码<br><https://bbs.77169.net/> |
| 飞客茶馆 | [wjf0214](https://github.com/wjf0214) | [飞客茶馆.har](https://raw.githubusercontent.com/qiandao-today/templates/master/飞客茶馆.har) | 2021-12-06 13:30:00 | username:账号,手机号<br>password:密码<br><https://www.flyert.com/><br>由于网站登录授权特殊,授权次数不固定。请求暂定3次，超过3次。可能登录不成功。多试几次便可 |
| V2EX | [github-h](https://github.com/github-h) | [V2EX.har](https://raw.githubusercontent.com/qiandao-today/templates/master/V2EX.har) | 2021-02-13 16:00:00 | cookie<br>若访问不稳定也建议添加hosts，目前应该只有 104.20.10.218 比较好用<br><https://www.v2ex.com/> |
| 花粉俱乐部 | [github-h](https://github.com/github-h) | [花粉俱乐部.har](https://raw.githubusercontent.com/qiandao-today/templates/master/花粉俱乐部.har) | 2021-02-13 16:00:00 | cookie<br><https://club.huawei.com/> |
| IT天空 | [github-h](https://github.com/github-h) | [IT天空.har](https://raw.githubusercontent.com/qiandao-today/templates/master/IT天空.har) | 2021-02-13 16:00:00 | cookie<br><https://www.itsk.com/> |
| 恩山无线论坛 | [github-h](https://github.com/github-h) | [恩山无线论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/恩山无线论坛.har) | 2021-03-10 16:00:00 | cookie<br>每日登录奖励<br>若签到不稳定也请自行添加hosts<br><https://www.right.com.cn/forum/forum.php> |
| 万能福利吧 | [github-h](https://github.com/github-h) | [万能福利吧.har](https://raw.githubusercontent.com/qiandao-today/templates/master/万能福利吧.har) | 2022-12-23 16:00:00 | cookie<br><https://www.wnflb2023.com/forum.php> |
| 高清MP4粉 | [github-h](https://github.com/github-h) | [高清MP4粉.har](https://raw.githubusercontent.com/qiandao-today/templates/master/高清MP4粉.har) | 2021-06-29 16:00:00 | cookie<br>每日签到<br><https://mp4fan.org/> |
| 漫画补档(账号密码版) | [wjf0214](https://github.com/wjf0214)  | [漫画补档(账号密码版).har](https://raw.githubusercontent.com/qiandao-today/templates/master/漫画补档(账号密码版).har) | 2020-12-02 20:00:00 |  username:账号<br>password:密码<br><https://www.manhuabudang.com> |
| 什么值得买7合一 |  [a76yyyy](https://github.com/a76yyyy) <br> [wjf0214](https://github.com/wjf0214) | [什么值得买7合一.har](https://raw.githubusercontent.com/qiandao-today/templates/master/什么值得买7合一.har) | 2020-12-08 17:10:00 |  登录后首页cookie,content1,content2,content3为评论语句，有字数限制。不想评论的不填就行，不影响签到。<br><https://smzdm.com> |
| 联想智选app | [aragonsnow](https://github.com/aragonsnow) | [联想智选app.har](https://raw.githubusercontent.com/qiandao-today/templates/master/联想智选app.har) | 2020-08-03 15:00:21 | 需要在联想智选APP 账号密码登录抓包 <br> account 和 password 是app登录的账号密码, loginType,邮箱是email,手机号是msisdn <br> IMEI 和 baseinfo 在 抓包的 <https://api.club.lenovo.cn/users/getSessionID> 的header里 <br> deviceId 在  抓包的 <https://uss.lenovomm.com/authen/1.2/tgt/user/get> 的post里 |
| 隔壁网 | [stay](https://gitee.com/qypw) | [隔壁网签到.har](https://raw.githubusercontent.com/qiandao-today/templates/master/隔壁网签到.har) | 2020-11-14 15:00:21 | username 和 password 是登录的账号密码 |
| MIUI历史版本 | [stay](https://gitee.com/qypw) | [MIUI历史版本.har](https://raw.githubusercontent.com/qiandao-today/templates/master/MIUI历史版本.har) | 2020-11-14 15:00:50 | username 和 password 是登录的账号密码 |
| E次元 |  [wjf0214](https://github.com/wjf0214)  | [E次元.har](https://raw.githubusercontent.com/qiandao-today/templates/master/E次元.har) | 2021-12-08 22:00:00 | homeaction和cks 打开首页即可获取 <https://www.evacg.cc/wp-admin/admin-ajax.php?action=> <br> <https://www.evacg.cc/cc/wp-admin/admin-ajax.php?action> |
| 数码之家 | [acooler15](https://github.com/acooler15) | [数码之家.har](https://raw.githubusercontent.com/qiandao-today/templates/master/数码之家.har) | 2021-06-28 20:24:00 | cookies |
| 迅维网 | [acooler15](https://github.com/acooler15) | [迅维网.har](https://raw.githubusercontent.com/qiandao-today/templates/master/迅维网.har) | 2022-03-02 23:00:00 | username:账号<br>password:密码<br><https://www.chinafix.com> |
| 远景论坛 | [acooler15](https://github.com/acooler15) | [远景论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/远景论坛.har) | 2021-06-28 20:24:00 | cookies |
| 91tvg主机玩家的营地 |  [wjf0214](https://github.com/wjf0214)  | [91tvg主机玩家的营地.har](https://raw.githubusercontent.com/qiandao-today/templates/master/91tvg主机玩家的营地.har) | 2021-12-10 13:30:00 |  登录后首页cookie<br><https://www.91tvg.com/> |
| 致美化 |  [wjf0214](https://github.com/wjf0214)  | [致美化.har](https://raw.githubusercontent.com/qiandao-today/templates/master/致美化.har) | 2021-11-20 21:20:00 |  user:账号<br>pass:密码<br><https://zhutix.com> |
| hao4k |  [wjf0214](https://github.com/wjf0214)  | [hao4k.har](https://raw.githubusercontent.com/qiandao-today/templates/master/hao4k.har) | 2022-03-02 21:30:00 |  登录后首页cookie,f12的时候请选中复制,不要右键复制值。<br><https://www.hao4k.cn/> |
| 掘金 | [acooler15](https://github.com/acooler15) | [掘金.har](https://raw.githubusercontent.com/qiandao-today/templates/master/掘金.har) | 2022-05-15 21:00:00 | cookies |
| 有道云笔记 | [acooler15](https://github.com/acooler15) | [有道云笔记.har](https://raw.githubusercontent.com/qiandao-today/templates/master/有道云笔记.har) | 2021-09-16 19:00:00 | cookies |
| 爱奇艺 | [a76yyyy](https://github.com/a76yyyy) | [爱奇艺.har](https://raw.githubusercontent.com/qiandao-today/templates/master/爱奇艺.har) | 2022-10-05 20:00:00 | 网址: https://www.iqiyi.com/; <br>首页登录后在cookie中提取变量P00001, P00003 和 _dfp变量中@符号前的部分内容; <br>仅爱奇艺会员可用 |
| MZFastCloud | [wjf0214](https://github.com/wjf0214) | [MZFastCloud.har](https://raw.githubusercontent.com/qiandao-today/templates/master/MZFastCloud.har) | 2021-11-20 21:00:00 | username:账号<br>password:密码<br><https://www.mzfast.xyz/> |
| HiFiNi | [wjf0214](https://github.com/wjf0214) | [HiFiNi.har](https://raw.githubusercontent.com/qiandao-today/templates/master/HiFiNi.har) | 2021-11-20 21:00:00 | 登录后首页cookie<br><https://www.hifini.com/> |
| 人人素材 | [wjf0214](https://github.com/wjf0214) | [人人素材.har](https://raw.githubusercontent.com/qiandao-today/templates/master/人人素材.har) | 2021-11-20 21:00:00 | username:账号,手机号<br>password:密码<br><https://www.rrcg.cn/> |
| SolidWorks机械工程师网 | [wjf0214](https://github.com/wjf0214) | [SolidWorks机械工程师网.har](https://raw.githubusercontent.com/qiandao-today/templates/master/SolidWorks机械工程师网.har) | 2021-12-02 20:00:00 | username:账号<br>password:密码<br><https://www.swbbsc.com/> |
| 卡饭(Cookie版) | [wjf0214](https://github.com/wjf0214) | [卡饭(Cookie版).har](https://raw.githubusercontent.com/qiandao-today/templates/master/卡饭(Cookie版).har) | 2022-04-29 10:40:00 | 登录后首页cookie<br><https://bbs.kafan.cn/> |
| hostloc主机论坛 | [wjf0214](https://github.com/wjf0214) | [hostloc主机论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/hostloc主机论坛.har) | 2021-11-20 22:30:00 | 登录后首页cookie<br><https://hostloc.com> |
| 粤梦缘 | [wjf0214](https://github.com/wjf0214) | [粤梦缘.har](https://raw.githubusercontent.com/qiandao-today/templates/master/粤梦缘.har) | 2021-11-20 22:30:00 | username:账号<br>password:密码<br><https://www.dranime.net/> |
| 幕后Muhou | [wjf0214](https://github.com/wjf0214) | [幕后Muhou.har](https://raw.githubusercontent.com/qiandao-today/templates/master/幕后Muhou.har) | 2021-12-31 09:30:00 | username:账号<br>password:密码<br><https://muhou.net/> |
| 一酷C4D | [wjf0214](https://github.com/wjf0214) | [一酷C4D.har](https://raw.githubusercontent.com/qiandao-today/templates/master/一酷C4D.har) | 2021-11-20 22:30:00 | 登录后首页cookie<br><https://c4dco.com> |
| Fa米家 | [wjf0214](https://github.com/wjf0214) | [Fa米家.har](https://raw.githubusercontent.com/qiandao-today/templates/master/Fa米家.har) | 2021-11-21 00:00:00 | 抓包 APP 的请求中的 headers 信息,提取 token、deviceId、blackBox 即可,fmVersion,os,User-Agent等参数可以根据自身情况自行更改。<br>应用单点登录限制，换设备登录后，之前登录状态参数失效 |
| 中国汉化论坛 | [wjf0214](https://github.com/wjf0214) | [中国汉化论坛.har](https://raw.githubusercontent.com/qiandao-today/templates/master/中国汉化论坛.har) | 2021-12-03 11:00:00 | username:账号<br>password:密码<br>questionId对应值：<br>-1.自定义问题<br>1.我爸爸的出生地<br>2.我妈妈的出生地<br>3.我的小学校名<br>4.我的中学校名<br>5.我最喜欢的运动<br>6.我最喜欢的歌曲<br>7.我最喜欢的电影<br>8.我最喜欢的颜色<br>customquest：自定义问题<br>answer:问题答案<br>没有密保安全问题，questionId,customquest,answer不填为空。<br><http://h.shanse8.com/> |
| HDDolby | [a76yyyy](https://github.com/a76yyyy) | [HDDolby.har](https://raw.githubusercontent.com/qiandao-today/templates/master/HDDolby.har) | 2022-12-15 20:00:00 | 登录后首页cookie<br><https://www.hddolby.com/index.php> |
| 不移之火 | [wjf0214](https://github.com/wjf0214) | [不移之火.har](https://github.com/qiandao-today/templates/blob/master/不移之火.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.byzhihuo.com/> |
| 次元狗 | [wjf0214](https://github.com/wjf0214) | [次元狗.har](https://github.com/qiandao-today/templates/blob/master/次元狗.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.acgndog.com/> |
| 好家伙机场 | [wjf0214](https://github.com/wjf0214) | [好家伙机场.har](https://github.com/qiandao-today/templates/blob/master/好家伙机场.har) | 2021-11-29 16:00:00 | email:邮箱<br>passwd:密码<br><https://haojiahuo.live/> |
| 后期菌资源村 | [wjf0214](https://github.com/wjf0214) | [后期菌资源村.har](https://github.com/qiandao-today/templates/blob/master/后期菌资源村.har) | 2021-11-29 16:00:00 | username:手机号<br>password:密码<br><http://www.houqijun.vip/> |
| 几鸡 | [wjf0214](https://github.com/wjf0214) | [几鸡.har](https://github.com/qiandao-today/templates/blob/master/几鸡.har) | 2021-11-29 16:00:00 | username:账号<br>password:密码<br>domain：网站域名 |
| 晋江小说 | [wjf0214](https://github.com/wjf0214) | [晋江小说.har](https://github.com/qiandao-today/templates/blob/master/晋江小说.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://m.jjwxc.net/> |
| 经管之家 | [wjf0214](https://github.com/wjf0214) | [经管之家.har](https://github.com/qiandao-today/templates/blob/master/经管之家.har) | 2021-12-08 22:00:00 | 登录后首页cookie<br><https://bbs.pinggu.org/> |
| 看雪安全论坛 | [wjf0214](https://github.com/wjf0214) | [看雪安全论坛.har](https://github.com/qiandao-today/templates/blob/master/看雪安全论坛.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://bbs.pediy.com/> |
| 科技玩家 | [wjf0214](https://github.com/wjf0214) | [科技玩家.har](https://github.com/qiandao-today/templates/blob/master/科技玩家.har) | 2021-11-29 16:00:00 | username:账号<br>password:密码<br><https://www.kejiwanjia.com/> |
| 科学刀论坛 | [wjf0214](https://github.com/wjf0214) | [科学刀论坛.har](https://github.com/qiandao-today/templates/blob/master/科学刀论坛.har) | 2022-10-09 16:00:00 | 登录后首页cookie<br><https://www.k7d.com/> |
| 科学刀在线时间 | [wjf0214](https://github.com/wjf0214) | [科学刀在线时间.har](https://github.com/qiandao-today/templates/blob/master/科学刀在线时间.har) | 2022-04-24 13:40:00 | 登录后首页cookie<br><https://www.k7d.com/> |
| 龙的天空 | [wjf0214](https://github.com/wjf0214) | [龙的天空.har](https://github.com/qiandao-today/templates/blob/master/龙的天空.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.lkong.com/> |
| 猫耳FM-每日鱼干 | [wjf0214](https://github.com/wjf0214) | [猫耳FM-每日鱼干.har](https://github.com/qiandao-today/templates/blob/master/猫耳FM-每日鱼干.har) | 2021-12-08 22:00:00 | 登录后首页cookie<br><https://www.missevan.com> |
| 魅族社区 | [wjf0214](https://github.com/wjf0214) | [魅族社区.har](https://github.com/qiandao-today/templates/blob/master/魅族社区.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://bbs.meizu.cn/> |
| 轻之文库 | [wjf0214](https://github.com/wjf0214) | [轻之文库.har](https://github.com/qiandao-today/templates/blob/master/轻之文库.har) | 2021-11-29 16:00:00 | username:账号<br>password:密码<br><https://www.linovel.net/> |
| 人人字幕组 | [wjf0214](https://github.com/wjf0214) | [人人字幕组.har](https://github.com/qiandao-today/templates/blob/master/人人字幕组.har) | 2022-02-10 23:35:00 | username:账号<br>password:密码<br>DOMAIN：网站域名【<https://www.yysub.net/>】 |
| 绅士领域 | [wjf0214](https://github.com/wjf0214) | [绅士领域.har](https://github.com/qiandao-today/templates/blob/master/绅士领域.har) | 2021-11-29 16:00:00 | uid:个人uid可APP抓签到包看到 |
| 时光相册 | [wjf0214](https://github.com/wjf0214) | [时光相册.har](https://github.com/qiandao-today/templates/blob/master/时光相册.har) | 2021-11-29 16:00:00 | phone:账号<br>password:密码<br>手机号密码 请抓登陆包查看 手机号里包括区号 86啥的 密码为加密后的密码<br><https://www.everphoto.cn/> |
| 手电大家谈 | [wjf0214](https://github.com/wjf0214) | [手电大家谈.har](https://github.com/qiandao-today/templates/blob/master/手电大家谈.har) | 2021-11-29 16:00:00 | username:账号<br>password:密码<br><https://www.shoudian.org/> |
| 书香门第 | [wjf0214](https://github.com/wjf0214) | [书香门第.har](https://github.com/qiandao-today/templates/blob/master/书香门第.har) | 2021-11-29 16:00:00 | account:账号<br>password:密码<br>登陆账号密码(只支持字母+数字组合账号)<br><http://www.txtnovel.top> |
| 王者营地 | [wjf0214](https://github.com/wjf0214) | [王者营地.har](https://github.com/qiandao-today/templates/blob/master/王者营地.har) | 2022-03-02 21:00:00 | 抓包 APP 中域名为 <https://ssl.kohsocialapp.qq.com> 请求内容的全部参数<br>APP自行商店下载 |
| 网易云游戏 | [wjf0214](https://github.com/wjf0214) | [网易云游戏.har](https://github.com/qiandao-today/templates/blob/master/网易云游戏.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://cg.163.com/> |
| 香网小说 | [wjf0214](https://github.com/wjf0214) | [香网小说.har](https://github.com/qiandao-today/templates/blob/master/香网小说.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://m.xiang5.com/> |
| 一加社区 | [wjf0214](https://github.com/wjf0214) | [一加社区.har](https://github.com/qiandao-today/templates/blob/master/一加社区.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.oneplusbbs.com/> |
| 阅次元论坛 | [wjf0214](https://github.com/wjf0214) | [阅次元论坛.har](https://github.com/qiandao-today/templates/blob/master/阅次元论坛.har) | 2021-12-17 13:10:00 | 登录后首页cookie<br><https://www.abooky.com/> |
| 中国原创音乐基地5SING | [wjf0214](https://github.com/wjf0214) | [中国原创音乐基地5SING.har](https://github.com/qiandao-today/templates/blob/master/中国原创音乐基地5SING.har) | 2021-11-29 16:00:00 | 登录后首页cookie,ck有效期一周<br><http://5sing.kugou.com/> |
| bigfun | [wjf0214](https://github.com/wjf0214) | [bigfun.har](https://github.com/qiandao-today/templates/blob/master/bigfun.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.bigfun.cn> |
| chiphell | [wjf0214](https://github.com/wjf0214) | [chiphell.har](https://github.com/qiandao-today/templates/blob/master/chiphell.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.chiphell.com> |
| element3ds | [wjf0214](https://github.com/wjf0214) | [element3ds.har](https://github.com/qiandao-today/templates/blob/master/element3ds.har) | 2022-01-06 10:00:00 | 登录后首页cookie<br><https://www.element3ds.com/> |
| HDarea高清视界 | [wjf0214](https://github.com/wjf0214) | [HDarea高清视界.har](https://github.com/qiandao-today/templates/blob/master/HDarea高清视界.har) | 2021-11-29 16:00:00 | 登录后首页cookie<br><https://www.hdarea.co/> |
| south-plus | [wjf0214](https://github.com/wjf0214) | [south-plus.har](https://github.com/qiandao-today/templates/blob/master/south-plus.har) | 2021-12-07 21:40:00 | 登录后首页cookie和UA<br>domain:为网站域名，如【https://www.south-plus.net/】,https和后面的'/'都要有<br><https://www.south-plus.net> |
| QooApp | [wjf0214](https://github.com/wjf0214) | [QooApp.har](https://github.com/qiandao-today/templates/blob/master/QooApp.har) | 2021-11-29 16:00:00 | token:下载App抓包cookie,找到请求头部 x-user-token 的值 |
| VCB-Studio分享论坛 | [wjf0214](https://github.com/wjf0214) | [VCB-Studio分享论坛.har](https://github.com/qiandao-today/templates/blob/master/VCB-Studio分享论坛.har) | 2021-12-08 22:00:00 | 登录后首页cookie<br><https://bbs.acgrip.com> |
| ZNDS智能电视网 | [wjf0214](https://github.com/wjf0214) | [ZNDS智能电视网.har](https://github.com/qiandao-today/templates/blob/master/ZNDS智能电视网.har) | 2021-11-29 16:00:00 | username:账号<br>password:密码<br><https://www.znds.com/> |
| 吾爱汇编 | [wjf0214](https://github.com/wjf0214) | [吾爱汇编.har](https://github.com/qiandao-today/templates/blob/master/吾爱汇编.har) | 2022-02-19 21:50:00 | 登录后首页cookie<br><https://www.52hb.com/> |
| 爱玩网络 | [wjf0214](https://github.com/wjf0214) | [爱玩网络.har](https://github.com/qiandao-today/templates/blob/master/爱玩网络.har) | 2021-12-01 11:10:00 | username:账号<br>password:密码<br><https://wngamebox.cn/> |
| switch520 | [wjf0214](https://github.com/wjf0214) | [switch520.har](https://github.com/qiandao-today/templates/blob/master/switch520.har) | 2021-12-06 16:30:00 | username:账号<br>password:密码<br><https://switch520.com/> |
| 远景论坛(账号版) | [wjf0214](https://github.com/wjf0214) | [远景论坛(账号版).har](https://github.com/qiandao-today/templates/blob/master/远景论坛(账号版).har) | 22021-12-08 22:00:00 | username:账号<br>password:密码<br><https://bbs.pcbeta.com/> |
| 小米运动 | [wjf0214](https://github.com/wjf0214) | [小米运动.har](https://github.com/qiandao-today/templates/blob/master/小米运动.har) | 2021-12-08 20:00:00 | username:账号<br>password:密码<br>min_step:最小步数<br>max_step:最大步数<br>步数在最大最小值之间取值，不填默认为1w到2w之间随机 |
| 阡陌居 | [wjf0214](https://github.com/wjf0214) | [阡陌居.har](https://github.com/qiandao-today/templates/blob/master/阡陌居.har) | 2021-12-10 09:45:00 | 登录后首页cookie<br>http://www.1000qm.vip/ |
| PtTime | [a76yyyy](https://github.com/a76yyyy) | [PtTime.har](https://github.com/qiandao-today/templates/blob/master/PtTime.har) | 2022-01-03 14:00:00 | 登录后首页cookie<br>https://www.pttime.org/ |
| ToTheGlory | [a76yyyy](https://github.com/a76yyyy) | [ToTheGlory.har](https://github.com/qiandao-today/templates/blob/master/ToTheGlory.har) | 2021-12-12 13:00:00 | 登录后首页cookie<br>https://totheglory.im/ |
| B站每日综合签到 | [嘉然今天吃什么](https://b23.tv/ufhdcOs) | [B站每日综合签到.har](https://github.com/qiandao-today/templates/blob/master/B站每日综合签到.har) | 2022-01-24 02:13:00 | 登录后首页cookie<br>https://www.bilibili.com/<br>每个操作都会相隔15秒。耐心等待，请不要重复点击测试！包含主站登陆经验+5视频观看经验+5视频分享经验+5,直播签到,B漫签到。带日志 |
| OB PT签到 账号密码版 | [嘉然今天吃什么](https://b23.tv/ufhdcOs) | [OBPT签到.har](https://github.com/qiandao-today/templates/blob/master/OBPT签到.har) | 2021-12-14 20:50:00 | OB站Cookie 30天过期一次，用账号密码版省心点 |
| 33iQ | [FellBan](https://github.com/FellBan) | [33iQ.har](https://github.com/qiandao-today/templates/blob/master/33iQ.har) | 2021-12-16 21:10:00 | user:账号<br>pass:密码<br><https://www.33iq.com/> |
| 万由论坛 | [FellBan](https://github.com/FellBan) | [万由论坛.har](https://github.com/qiandao-today/templates/blob/master/万由论坛.har) | 2021-12-16 21:10:00 | 登录后首页cookie<br><https://www.u-share.cn/> |
| 魔兽大数据 | [wjf0214](https://github.com/wjf0214) | [魔兽大数据.har](https://github.com/qiandao-today/templates/blob/master/魔兽大数据.har) | 2022-02-22 23:00:00 | 登录后首页cookie<br>content：世界频道发言的内容<br><http://bj.wowdata.top/> |
| 龙de船人 | [wjf0214](https://github.com/wjf0214) | [龙de船人.har](https://github.com/qiandao-today/templates/blob/master/龙de船人.har) | 2022-03-31 13:45:00 | 登录后首页cookie<br><https://www.imarine.cn/> |
| 新赚吧 | [wjf0214](https://github.com/wjf0214) | [新赚吧.har](https://github.com/qiandao-today/templates/blob/master/新赚吧.har) | 2021-12-28 13:00:00 | username:账号<br>password:密码<br><https://v1.xianbao.net/> |
| SSPANEL机场通用签到 | [wjf0214](https://github.com/wjf0214) | [SSPANEL机场通用签到.har](https://github.com/qiandao-today/templates/blob/master/SSPANEL机场通用签到.har) | 2021-12-28 14:20:00 | domain:域名,如【https://xxx.com】,后面不带'/'<br>username:账号<br>password:密码 |
| 萌盘总动员 | [wjf0214](https://github.com/wjf0214) | [萌盘总动员.har](https://github.com/qiandao-today/templates/blob/master/萌盘总动员.har) | 2021-12-30 14:00:00 | username:账号<br>password:密码<br><http://bdarea.net/> |
| 98堂 | [wjf0214](https://github.com/wjf0214) | [98堂.har](https://github.com/qiandao-today/templates/blob/master/98堂.har) | 2021-12-31 15:00:00 | username:账号<br>password:密码<br><https://wetytrytuyu.net/> |
| 学犀牛中文网 | [wjf0214](https://github.com/wjf0214) | [学犀牛中文网.har](https://github.com/qiandao-today/templates/blob/master/学犀牛中文网.har) | 2021-12-31 15:00:00 | 登录后首页cookie，不要右键复制值，请选中后复制<br><https://www.xuexiniu.com/> |
| 大碗岛漫画 | [wjf0214](https://github.com/wjf0214) | [大碗岛漫画.har](https://github.com/qiandao-today/templates/blob/master/大碗岛漫画.har) | 2021-12-31 16:00:00 | username:账号<br>password:密码<br><http://www.dawandao.com/> |
| 捌零发烧音乐网 | [wjf0214](https://github.com/wjf0214) | [捌零发烧音乐网.har](https://github.com/qiandao-today/templates/blob/master/捌零发烧音乐网.har) | 2022-01-03 10:00:00 | 登录后首页cookie<br><https://hifi.juyincar.com/> |
| 武聆音雄配乐网 | [wjf0214](https://github.com/wjf0214) | [武聆音雄配乐网.har](https://github.com/qiandao-today/templates/blob/master/武聆音雄配乐网.har) | 2021-12-31 15:00:00 | username:账号<br>password:密码<br>message:签到回复帖子的语句，默认为'每日签到~'<br><https://www.wlyxmusic.net/> |
| 56brand我来网 | [wjf0214](https://github.com/wjf0214) | [56brand我来网.har](https://github.com/qiandao-today/templates/blob/master/56brand我来网.har) | 2022-01-03 14:00:00 | username:账号<br>password:密码<br><http://www.56brand.com/> |
| 野火论坛 | [wjf0214](https://github.com/wjf0214) | [野火论坛.har](https://github.com/qiandao-today/templates/blob/master/野火论坛.har) | 2022-01-07 10:00:00 | username:账号<br>password:密码<br><http://www.proewildfire.cn/> |
| 3D溜溜网 | [wjf0214](https://github.com/wjf0214) | [3D溜溜网.har](https://github.com/qiandao-today/templates/blob/master/3D溜溜网.har) | 2022-01-06 09:30:00 | 登录后首页cookie<br><https://user.3d66.com/> |
| 宽带技术网 | [wjf0214](https://github.com/wjf0214) | [宽带技术网.har](https://github.com/qiandao-today/templates/blob/master/宽带技术网.har) | 2022-01-07 10:00:00 | 登录后首页cookie<br><http://www.chinadsl.net/> |
| 摩登犀牛 | [wjf0214](https://github.com/wjf0214) | [摩登犀牛.har](https://github.com/qiandao-today/templates/blob/master/摩登犀牛.har) | 2022-01-06 19:30:00 | username:账号<br>password:密码<br><http://bbs.rhino3d.us/> |
| Goldroom黄金屋 | [wjf0214](https://github.com/wjf0214) | [Goldroom黄金屋.har](https://github.com/qiandao-today/templates/blob/master/Goldroom黄金屋.har) | 2022-01-11 17:10:00 | 登录后首页cookie<br><http://goldroom.top/> |
| OpenFrp | [嘉然今天吃什么](https://b23.tv/ufhdcOs) | [OpenFrp.har](https://github.com/qiandao-today/templates/blob/master/OpenFrp.har) | 2022-01-24 02:13:00 | 登录后首页cookie<br><https://www.openfrp.net/> |
| 心动日剧 | [嘉然今天吃什么](https://b23.tv/ufhdcOs) | [心动日剧.har](https://github.com/qiandao-today/templates/blob/master/心动日剧.har) | 2022-01-25 01:36:00 | 账号密码版本，带日志<br><http://www.doki8.com/> |
| 河洛网 | [wjf0214](https://github.com/wjf0214) | [河洛网.har](https://github.com/qiandao-today/templates/blob/master/河洛网.har) | 2022-03-08 21:15:00 | username:账号<br>password:密码<br><https://www.horou.com/> |
| 落叶次元 | [wjf0214](https://github.com/wjf0214) | [落叶次元.har](https://github.com/qiandao-today/templates/blob/master/落叶次元.har) | 2022-02-07 22:40:00 | username:邮箱<br>password:密码<br><https://www.lyocy.com/> |
| tool.lu在线工具 | [wjf0214](https://github.com/wjf0214) | [tool.lu在线工具.har](https://github.com/qiandao-today/templates/blob/master/tool.lu在线工具.har) | 2022-02-21 10:00:00 | 登录后<https://id.tool.lu/profile>页面cookie<br><https://tool.lu/> |
| 小云社区 | [wjf0214](https://github.com/wjf0214) | [小云社区.har](https://github.com/qiandao-today/templates/blob/master/小云社区.har) | 2022-02-16 15:40:00 | username:账号<br>password:密码<br><https://www.xiaoyunbbs.cn/> |
| 我爱迅雷 | [wjf0214](https://github.com/wjf0214) | [我爱迅雷.har](https://github.com/qiandao-today/templates/blob/master/我爱迅雷.har) | 2022-02-16 16:10:00 | username:账号<br>password:密码<br><https://www.96yuedu.com/> |
| geekhub | [wjf0214](https://github.com/wjf0214) | [geekhub.har](https://github.com/qiandao-today/templates/blob/master/geekhub.har) | 2022-02-19 11:40:00 | username:账号<br>password:密码<br><https://www.geekhub.com/> |
| 52asus | [wjf0214](https://github.com/wjf0214) | [52asus.har](https://github.com/qiandao-today/templates/blob/master/52asus.har) | 2022-02-16 19:10:00 | username:账号<br>password:密码<br><https://www.52asus.com/> |
| eatASMR | [wjf0214](https://github.com/wjf0214) | [eatASMR.har](https://github.com/qiandao-today/templates/blob/master/eatASMR.har) | 2022-02-17 10:10:00 | username:账号<br>password:密码<br><https://eatasmr.com/> |
| 好书友 | [wjf0214](https://github.com/wjf0214) | [好书友.har](https://github.com/qiandao-today/templates/blob/master/好书友.har) | 2022-03-01 23:35:00 | username:账号<br>password:密码<br><https://www.58shuyou.com/> |
| 腾龙工作室 | [wjf0214](https://github.com/wjf0214) | [腾龙工作室.har](https://github.com/qiandao-today/templates/blob/master/腾龙工作室.har) | 2022-02-17 11:10:00 | username:邮箱<br>password:密码<br><https://www.tenlonstudio.com/> |
| 蓝光演唱会 | [wjf0214](https://github.com/wjf0214) | [蓝光演唱会.har](https://github.com/qiandao-today/templates/blob/master/蓝光演唱会.har) | 2022-02-18 17:40:00 | username:账号<br>password:密码<br><https://www.lgych.com/> |
| 原盘天堂 | [wjf0214](https://github.com/wjf0214) | [原盘天堂.har](https://github.com/qiandao-today/templates/blob/master/原盘天堂.har) | 2022-02-19 22:30:00 | username:账号<br>password:密码<br><https://4k3dyptt.com/> |
| WhereMyLife | [wjf0214](https://github.com/wjf0214) | [WhereMyLife.har](https://github.com/qiandao-today/templates/blob/master/WhereMyLife.har) | 2022-02-22 10:40:00 | username:邮箱<br>password:密码<br><https://wheremylife.cn/> |
| Gogo次元 | [wjf0214](https://github.com/wjf0214) | [Gogo次元.har](https://github.com/qiandao-today/templates/blob/master/Gogo次元.har) | 2022-02-22 15:00:00 | username:账号<br>password:密码<br><https://gogoacg.ws/> |
| blue高清公馆 | [wjf0214](https://github.com/wjf0214) | [blue高清公馆.har](https://github.com/qiandao-today/templates/blob/master/blue高清公馆.har) | 2022-02-22 20:00:00 | username:账号<br>password:密码<br><https://www.bluegq.com/> |
| 国配影迷社区 | [wjf0214](https://github.com/wjf0214) | [国配影迷社区.har](https://github.com/qiandao-today/templates/blob/master/国配影迷社区.har) | 2022-02-23 12:00:00 | 登录后首页cookie<br><https://club.ccmnn.com/> |
| 飘云阁 | [wjf0214](https://github.com/wjf0214) | [飘云阁.har](https://github.com/qiandao-today/templates/blob/master/飘云阁.har) | 2022-03-11 21:20:00 | username:账号<br>password:密码<br><https://www.chinapyg.com/> |
| 书法江湖 | [wjf0214](https://github.com/wjf0214) | [书法江湖.har](https://github.com/qiandao-today/templates/blob/master/书法江湖.har) | 2022-02-27 00:00:00 | username:账号<br>password:密码<br><https://www.shufajianghu.com/> |
| 全球VPS交流社区 | [FellBan](https://github.com/FellBan) | [全球VPS交流社区.har](https://github.com/qiandao-today/templates/blob/master/全球VPS交流社区.har) | 2022-03-19 00:00:00 | username:账号<br>password:密码<br><https://www.qqvps.com/> |
| 废文网 | [Ovler-Young](https://github.com/Ovler-Young) | [废文网.har](https://github.com/qiandao-today/templates/blob/master/废文网.har) | 2022-03-28 14:04:15 | 登录后首页cookie<br>uid(前往usercenter，地址中有)<br><https://废文网.com/> |
| 鸿鹄论坛 | [FellBan](https://github.com/FellBan) | [鸿鹄论坛.har](https://github.com/qiandao-today/templates/blob/master/鸿鹄论坛.har) | 2022-03-29 11:35:27 | 首页Cookie<br><https://bbs.hh010.com/> |
| 攻城狮论坛-CCNA论坛 | [FellBan](https://github.com/FellBan) | [攻城狮论坛-CCNA论坛.har](https://github.com/qiandao-today/templates/blob/master/攻城狮论坛-CCNA论坛.har) | 2022-03-29 11:35:27 | 首页Cookie<br><http://bbs.vlan5.com/> |
| 4K时光官网 | [FellBan](https://github.com/FellBan) | [4K时光官网.har](https://github.com/qiandao-today/templates/blob/master/4K时光官网.har) | 2022-04-07 17:32:00 | 首页Cookie<br><https://www.4ksg.com/> |
| 紫猫学院社区 | [FellBan](https://github.com/FellBan) | [紫猫学院社区.har](https://github.com/qiandao-today/templates/blob/master/紫猫学院社区.har) | 2022-04-14 16:28:00 | 首页Cookie<br><https://zimaoxy.com/b/forum.php> |
| 修图匠人 | [FellBan](https://github.com/FellBan) | [修图匠人.har](https://github.com/qiandao-today/templates/blob/master/修图匠人.har) | 2022-04-14 18:01:00 | 首页Cookie<br><https://www.tsliuyu.com/> |
| 糖果VR资源网 | [FellBan](https://github.com/FellBan) | [糖果VR资源网.har](https://github.com/qiandao-today/templates/blob/master/糖果VR资源网.har) | 2022-04-14 18:24:00 | 首页Cookie<br><https://www.tangguo2.com/forum.php> |
| HDTime | [wjf0214](https://github.com/wjf0214) | [HDTime.har](https://github.com/qiandao-today/templates/blob/master/HDTime.har) | 2022-04-16 18:24:00 | 首页Cookie<br><https://hdtime.org/> |
| 聆音Club | [wjf0214](https://github.com/wjf0214) | [聆音Club.har](https://github.com/qiandao-today/templates/blob/master/聆音Club.har) | 2022-04-16 18:24:00 | 首页Cookie<br><https://pt.soulvoice.club/> |
| MC百科 | [FellBan](https://github.com/FellBan) | [MC百科.har](https://github.com/qiandao-today/templates/blob/master/MC百科.har) | 2022-04-24 18:26:00 | 首页Cookie<br><https://center.mcmod.cn/> |
| MC百科账号版 | [FellBan](https://github.com/FellBan) <br> [AlisaCat-S](https://github.com/AlisaCat-S) | [MC百科账号版.har](https://github.com/qiandao-today/templates/blob/master/MC百科账号版.har) | 2022-07-17 11:09:00 | 用户名密码<br>可选自定义UA,空为默认UA<br><https://center.mcmod.cn/> |
| IT技术交流论坛 | [FellBan](https://github.com/FellBan) | [IT技术交流论坛.har](https://github.com/qiandao-today/templates/blob/master/IT技术交流论坛.har) | 2022-05-02 17:13:00 | 首页Cookie<br><https://bbs.itzmx.com/> |
| 苹果团 | [FellBan](https://github.com/FellBan) | [苹果团.har](https://github.com/qiandao-today/templates/blob/master/苹果团.har) | 2022-05-24 00:34:00 | 首页Cookie<br><https://appletuan.com/> |
| 游戏大桶 | [FellBan](https://github.com/FellBan) | [游戏大桶.har](https://github.com/qiandao-today/templates/blob/master/游戏大桶.har) | 2022-05-26 17:04:00 | 账号密码<br>定时-当天随机延时12000~20000 不随机容易出滑块就签到不了<br><https://gamekegs.com> |
| 4K视界 | [FellBan](https://github.com/FellBan) | [4K视界.har](https://github.com/qiandao-today/templates/blob/master/4K视界.har) | 2022-05-26 17:30:00 | 首页Cookie<br><https://www.4ksj.com/> |
| Cnlang国语视界 | [FellBan](https://github.com/FellBan) | [Cnlang国语视界.har](https://github.com/qiandao-today/templates/blob/master/Cnlang国语视界.har) | 2022-05-28 09:55:00 | 首页Cookie<br><https://cnlang.org/> |
| 速蛙云 | [a76yyyy](https://github.com/a76yyyy) | [速蛙云.har](https://github.com/qiandao-today/templates/blob/master/速蛙云.har) | 2022-05-28 12:00:00 | F12获取info请求 Cookie 和 authorizationmweb 参数, <br>domain: 速蛙云域名, 如 cloud.sw16.icu |
| FreeFarm | [AemonCao](https://github.com/AemonCao) | [FreeFarm.har](https://github.com/qiandao-today/templates/blob/master/FreeFarm.har) | 2022-05-28 12:00:00 | 首页Cookie<br>https://pt.0ff.cc/ |
| CarPT | [AemonCao](https://github.com/AemonCao) | [CarPT.har](https://github.com/qiandao-today/templates/blob/master/CarPT.har) | 2022-05-28 12:00:00 | 首页Cookie<br>https://carpt.net/ |
| m-team-PT签到(cookie版) | [devil](https://github.com/q123458384) | [m-team-PT签到(cookie版).har](https://raw.githubusercontent.com/qiandao-today/templates/master/m-team%EF%BC%88cookie%E7%89%88%EF%BC%89.har) | 2020-05-25 14:06:23 | cookie<br><https://kp.m-team.cc/> |
| m-team-PT签到(账号版) | [devil](https://github.com/q123458384) | [ m-team-PT签到(账号版).har](https://raw.githubusercontent.com/qiandao-today/templates/master/m-team%EF%BC%88%E8%B4%A6%E5%8F%B7%E5%AF%86%E7%A0%81%E7%89%88%EF%BC%89.har) | 2020-05-25 14:06:23 | username:账号<br>password:密码 |
| m-team-PT签到(FlareSolverr+cookie版) | [Sinkerine](https://github.com/15cm) | [m-team-cookie-flaresolverr.har](https://raw.githubusercontent.com/qiandao-today/templates/master/m-team-cookie-flaresolverr.har) | 2020-05-25 14:06:23 | cookies_value_tp: Cookies 中 "tp" key 的值<br>userid: userdetails.php?id={{userid}} 的用户 id<br>FlareSolverr url. 如 http://localhost:8191/v1|
| RainPat专利检索 | [FellBan](https://github.com/FellBan) | [RainPat专利检索.har](https://github.com/qiandao-today/templates/blob/master/RainPat专利检索.har) | 2022-05-30 10:10:00 | username:账号<br>password:密码<br><https://www.rainpat.com/> |
| 慢慢游社区 | [FellBan](https://github.com/FellBan) | [慢慢游社区.har](https://github.com/qiandao-today/templates/blob/master/慢慢游社区.har) | 2022-05-30 10:10:00 | 首页Cookie<br><https://www.mmybt.com/> |
| 布谷Tv | [FellBan](https://github.com/FellBan) | [布谷Tv.har](https://github.com/qiandao-today/templates/blob/master/布谷Tv.har) | 2022-06-05 17:25:00 | username:账号<br>password:密码<br><https://www.bugutv.net/> |
| 元宇宙创意 | [FellBan](https://github.com/FellBan) | [元宇宙创意.har](https://github.com/qiandao-today/templates/blob/master/元宇宙创意.har) | 2022-06-06 09:31:00 | username:账号<br>password:密码<br><https://mult.utour.top/> |
| NicePT | [FrostKMR](https://github.com/FrostKMR) | [nicept.har](https://github.com/qiandao-today/templates/blob/master/nicept.har) | 2022-07-11 06:55:00 | 首页Cookie<br><https://nicept.net/> |
| HDHome | [AlisaCat-S](https://github.com/AlisaCat-S) | [hdhome.har](https://raw.githubusercontent.com/qiandao-today/templates/master/hdhome.har) | 2022-07-17 10:26:00 | HDHome家园<br>首页Cookie<br>自定义UA:可选,空为默认UA<br>国内访问经常超时<br><https://hdhome.org/> |
| MyQQ | [FellBan](https://github.com/FellBan) | [MyQQ.har](https://github.com/qiandao-today/templates/blob/master/MyQQ.har) | 2022-07-05 19:58:00 | 首页Cookie<br><https://bbs.myqqx.net> |
| 老男人游戏网配套论坛 | [FellBan](https://github.com/FellBan) | [老男人游戏网配套论坛.har](https://github.com/qiandao-today/templates/blob/master/老男人游戏网配套论坛.har) | 2022-07-05 19:58:00 | 首页Cookie<br><https://bbs.oldmanemu.net/> |
| 掌上百科账号版 | [AlisaCat-S](https://github.com/AlisaCat-S) | [掌上百科账号版.har](https://github.com/qiandao-today/templates/blob/master/掌上百科账号版.har) | 2022-07-05 19:58:00 | 用户名密码,转盘次数与种树时间可自行调整<br>签到+种树+兑换+转盘抽奖<br><https://www.pdawiki.com/> |
| PT通用登录保号 | [bipy](https://github.com/bipy) | [PT通用登录保号.har](PT通用登录保号.har) | 2022-07-31 19:30:00 | domain:域名, 如 pt.somept.com <br> cookie: PT的Cookie|
| 成都吃喝玩乐网 | [FellBan](https://github.com/FellBan) | [成都吃喝玩乐网.har](https://github.com/qiandao-today/templates/blob/master/成都吃喝玩乐网.har) | 2022-09-02 00:33:00 | 首页Cookie<br><https://www.52ch.net/> |
| SF轻小说 | [chen8945](https://github.com/chen8945) | [SF轻小说.har](https://github.com/qiandao-today/templates/blob/master/SF轻小说.har) | 2022-10-06 01:10:00 | 每日签到和阅读时长任务，需要在凌晨一点后执行（相应数据需要在APP抓包）<br><https://www.sfacg.com/> |
| 爱桌游 | [chen8945](https://github.com/chen8945) | [爱桌游.har](https://github.com/qiandao-today/templates/blob/master/爱桌游.har) | 2022-09-27 13:40:00 | 首页Cookie<br><https://www.lovezhuoyou.com/> |
| DJI大疆社区 | [chen8945](https://github.com/chen8945) | [DJI大疆社区.har](https://github.com/qiandao-today/templates/blob/master/DJI大疆社区.har) | 2022-10-05 21:25:00 | 首页Cookie<br><https://bbs.dji.com/> |
| 白兔俱乐部 | [AlisaCat-S](https://github.com/AlisaCat-S) | [白兔俱乐部.har](https://github.com/qiandao-today/templates/blob/master/白兔俱乐部.har) | 2022-10-06 12:25:00 | 首页Cookie<br><https://club.hares.top/> |
| 小栗子社区 | [chen8945](https://github.com/chen8945) | [小栗子社区.har](https://github.com/qiandao-today/templates/blob/master/小栗子社区.har) | 2022-10-08 16:20:00 | 首页Cookie，Cookie请选中复制，不要右键复制<br><https://f.xiaolz.cn/> |
| 华印社区 | [chen8945](https://github.com/chen8945) | [华印社区.har](https://github.com/qiandao-today/templates/blob/master/华印社区.har) | 2022-10-17 00:20:00 | 用户名+密码<br><https://www.52cnp.com/> |
| 360积分中心 | [chen8945](https://github.com/chen8945) | [360积分中心.har](https://github.com/qiandao-today/templates/blob/master/360积分中心.har) | 2022-11-19 01:00:00 | 首页Cookie<br><https://jf.360.cn/> |
| 9DM玖大猫 | [chen8945](https://github.com/chen8945) | [9DM玖大猫.har](https://github.com/qiandao-today/templates/blob/master/9DM玖大猫.har) | 2022-11-27 14:10:00 | 用户名+密码<br>用户名含有中文或者特殊字符请使用另一个邮箱版<br><http://www.9damaogame.net/> |
| 9DM玖大猫邮箱版 | [chen8945](https://github.com/chen8945) | [9DM玖大猫邮箱版.har](https://github.com/qiandao-today/templates/blob/master/9DM玖大猫邮箱版.har) | 2022-11-27 14:20:00 | 邮箱+密码<br>用户名位置填邮箱<br><http://www.9damaogame.net/> |
| SSDForum | [chen8945](https://github.com/chen8945) | [SSDForum.har](https://github.com/qiandao-today/templates/blob/master/SSDForum.har) | 2022-11-29 01:50:00 | 首页Cookie，Cookie请选中复制，不要右键复制<br><https://ssdforum.org/> |
| 影视168论坛 | [chen8945](https://github.com/chen8945) | [影视168论坛.har](https://github.com/qiandao-today/templates/blob/master/影视168论坛.har) | 2022-11-29 01:50:00 | 首页Cookie，Cookie请选中复制，不要右键复制<br><http://hkdy168.com/> |
| 狮碟论坛 | [chen8945](https://github.com/chen8945) | [狮碟论坛.har](https://github.com/qiandao-today/templates/blob/master/狮碟论坛.har) | 2022-11-29 01:50:00 | 首页Cookie，Cookie请选中复制，不要右键复制<br><http://www.ssdvd.net/> |
| 云原神 | [chen8945](https://github.com/chen8945) | [云原神.har](https://github.com/qiandao-today/templates/blob/master/云原神.har) | 2022-11-30 20:00:00 | APP抓包 x-rpc-combo_token和x-rpc-device_id<br>每日 04:00 刷新签到时间，定时请设置在4点以后<br><https://mhyy.mihoyo.com/> |

## 📄如何注册第三方库

20211021版本已经开放注册第三方库的功能，默认提供 <https://github.com/qiandao-today/templates> 仓库，如果需要自建第三方库，请注意一下几点：

1. **仓库根目录必须要有 `tpls_history.json` 文件**, 需符合以下规范:

    ```json
    {
        "version":"版本号 yyyymmdd",
        "har": {
            "必填，和name保值一致，注意要在文件里保持唯一": {
                "name": "必填", 
                "author": "选题，作者", 
                "url": "选填，har链接", 
                "update": false, 
                "comments": "选填，har文件的注释，可用来解释har所需变量的说明", 
                "filename": "必填，content为空时通过此来读取har", 
                "content": "选填,不填则根据 filename 的值来读取对应的har文件,默认为base64编码", 
                "date": "必填， 日期",
                "version":"必填， 版本号 yyyymmdd，框架通过版本号来判断是否更新模板",
                "commenturl":"选填，模板对应的评论区，留空时不显示按钮"
            }
        }
    }
    ```

2. 加速默认是 `jsdeliver` 加速, 只支持 `Github` 的加速
3. 模板更新规则: 上一次更新的24小时以后更新, 通过 `name` 判断是否存在, 如果不存在直接新增, 如果存在则通过 `version` 判断, 版本号大于当前缓存版本则更新

## 💬FAQ

**部分模板订阅后使用网站cookie却提示未登录？**

并不是模板问题而是网站可能对UA有验证，UA更换cookie会失效。请自行查看模板所使用的 User-Agent ,并使用所获得的UA去登录获取cookie。( Firefox 可使用 User-Agent Switcher and Manager 来设置特定的UA，其他浏览器同理。)

**想学习模板制作流程？**

[签到宝典demo](https://www.bilibili.com/video/BV1ox411C7RT)

[模板书写规范](https://github.com/github-h/qiandao-templates/blob/self-bak/README.md)

## 💝鸣谢

- [gxitm](https://github.com/gxitm)
- [AragonSnow](https://github.com/AragonSnow)
- [FellBan](https://github.com/FellBan)
- [Devil](https://github.com/q123458384)
- [github-h](https://github.com/github-h)
- [liuqitech](https://github.com/liuqitoday)
- 呆贼
- [stay](https://gitee.com/qypw)
- [acooler15](https://github.com/acooler15)
- [wjf0214](https://github.com/wjf0214)
- [a76yyyy](https://github.com/a76yyyy)
