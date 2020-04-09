# AncientChinaCurrencyConverter
中国古代货币换算器(ACCC)

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