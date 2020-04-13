# AncientCurrencyConverter
古代银钱换算器(ACC)

**算法公式：** 底层工人、百姓勉强维持温饱的月入（银两、文钱、布帛、银元）=现如今底层工人、百姓勉强维持温饱的月入（人民币）

## DEMO
![demo]()
![小程序码]()

## 运行平台
微信小程序、支付宝小程序、H5、ios、安卓

使用 uni-app 开发，除微信小程序外，其他端未测试

## 框架/工具
- uni-app
- 算法规则依据 https://zhuanlan.zhihu.com/p/32089267
- 

ps: 王朝末期时，往往金钱会大量贬值，导致经济崩盘，所以在选用朝代基础价格时，会选用朝代中较为稳定的时期。

朝代 | 时期 | 流通货币 | 月收入 | 汇率 | 出处
---|---|---|---|---|---
中国 | 2019 | 人民币 | 3000 | 1:1| 北京市人力资源和社会保障局：关于调整北京市2019年最低工资标准的通知，京人社劳发[2019]71号，最低工资为2200元
民国 | 1918（民国7年） | 银元 | 2 | 1:1500 | 西德尼 • D. 甘博：《北京的社会调查》，北京：中国书店，2010 年，第 286—289 页。北京居民最底层的收入是1.66银元/月
清朝 | 1737(乾隆二年) | 两 | 16 | 1:187.5 | 中国第一历史档案馆刑科题本乾隆命案档，档号1056，直隶大兴县，长工月例16两
明朝 | 1608(万历三十六年) | 文 | 30 | 1:100 | 《续文献通老》卷——《钱币五》，北平，工钱三十文上下
元朝 | 1333(至顺元年) | 贯 | 20 | 1:150 | 《黑城出土文书》下《叁民籍类》P.188，内蒙古黑城，月工中统钞20贯
南宋 | 1127(靖康二年) | 文 | 1000 | 1:3 | 《夷坚支至》卷一《茶仆崔三》，黄州，月工1000文
北宋 | 1067(英宗时期) | 文 | 3780 | 1:0.79 | 朱彧：《萍州可谈》卷一，汴京，每日126文
唐 | 627-742(盛唐时期) | 文 | 1080 | 1:2.8 | 《唐六典·户部》卷三，每日绢三尺（约钱36文）
东汉 | 25年—220年 | 钱 | 1000 | 1:3 | 崔寔:《政论》，北方，月千钱
西汉 | 前202年—公元8年| 钱 | 2000 | 1:1.5 | 《汉书·沟洫志》，北方，治黄河河工，一月，钱二千


## 功能需求
- [ ] 清空数据
- [ ] 报警监控(二期)
- [ ] 我要吐槽-意见反馈
- [ ] 彩蛋 （等待你的发现~~）
- [x] 转发分享
- [ ] 适配小程序pc（ipad）端
- [ ] 支付宝版小程序
- [ ] H5版
- [ ] 各朝代货币图片及介绍，折叠面板，图片点击放大
- [ ] 国外货币换算

## 更新日志
### 0.1.0
- 【初始化】

## 技巧
### css绝对定位(absolute)居中方法
```
.panel {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}
```