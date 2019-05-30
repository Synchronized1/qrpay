# qrpay
五合一收款码在线生成,35个模板 支持微信支付、支付宝支付、手机QQ支付、京东钱包、百度钱包,五合一收款，将其二维码合并为一个二维码，无需手续费,支持qq头像,昵称判断(HTML单页版多模板免安装)
# 演示站
腾讯云服务器 https://api.isoyu.com/qrpay/ 

腾讯云COS https://qrpay.isoyu.com/

# 相关源码
微信小程序版源码:https://github.com/insoxin/weapp-qrpay

二维码生成与解码:https://github.com/insoxin/API
## 常见问题
1.合并后的收款码有扫码次数和时间限制吗？
无限制扫码次数；永久可用。

2.合并后的二维码安全吗？
安全。技术上，我们只是对五种类型的收款码进行合并，让用户收款使用更方便

3.别人扫码付款后，钱打到哪里去了？
打到您的个人账户。具体来说：微信扫码付款时，钱打到您的微信钱包里；支付宝扫码付款时，钱打到您的支付宝账户里；QQ扫码付款时，钱打到您的QQ钱包里；京东扫码付款时，钱打到您的京东钱包里；百度扫码付款时，钱打到您的百度钱包里

4.为什么微信、QQ扫码后还需要长按识别？
微信、QQ接口未开放权限，无法直接调起微信、QQ转账页面，所以需要长按识二维码别进行转账。（给您带来不便还请谅解）目前支付宝接口已开放权限。可以直接扫码付款。

5.使用此功能时，微信支付、支付宝支付、手机QQ支付、京东钱包、百度钱包,会向我收取费用吗？
不会。此功能是对二维码进行合并，不涉及微信、支付宝、QQ、京东、百度的收费问题。

6.在网站上传收款码会泄露用户隐私资料吗？

不会。收款码是个人的收款二维码，是客户向对方转账的一种方式，和商家平时向客户展示的收款码是一样的。

7.合并后的二维码能通过微信或者支付宝或者QQ或者京东扫码转账码？
可以。通过合并后的二维码可以自动识别用户扫码方式，微信扫码则使用微信支付，支付宝扫码则使用支付宝支付，QQ扫码则使用QQ支付,京东扫码则使用京东支付,百度扫码则使用百度支付

8.合并二维码对于商家有什么好处？
①对于商家来说可免中间手续费，收款直接转入到商家个体账户，不需经过第三方公司提现。

②一码在手，随扫随有：只保留一个扫码牌就可以了。

③此功能免费使用

9.模板更新
①目前可使用35套模板(2019.04.04)
(21,py交易,由 @海峰 提供
②看到好看的二维码可以点击底部 问题反馈 发送给我

GitHub：五合一收款码 
本站托管在腾讯COS中！立即赞助 
部分特殊二维码若识别不出,请到https://cli.im/deqr 识别后复制过来继续
