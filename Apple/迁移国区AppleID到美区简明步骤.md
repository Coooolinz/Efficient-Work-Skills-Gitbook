*有效时间:2017-8-5*

# 国区Apple ID迁移到美区简要方法

## 背景

因为近期国内政策原因，导致诸多上网应用被集体下架，后续动态也不明朗，站在这个时间点看尽早将国区ID迁移到美区/其他区是比较理想的选择。

### 迁移的目的

- 由国区迁移到美区
- 可以使用PayPal进行购买

*如果临时切换可直接切换到加拿大并选择None支付方式进行切换*

### 迁移优缺点

- 优点
  - 美区资源丰富，还可以下到其他丰富的App或内容
    - Google、Spotify……
    - 购买Apple Music专辑、音乐
    - 图书
    - 电影
  - 且ZF暂时未将触手伸到美区，相对安全
- 缺点
  - 迁移操作复杂
    - 准备资料
      - 涉及美国信用卡/Paypal
      - 美国手机号
      - 美国地址
  - 迁移有一定成本
  -  *封号危险？*
  - 后续使用成本高
    - 美区没有1元应用，最低0.99元应用
    - *网络质量差？*
      - 是否走国内CDN
    - 支付只能Paypal、Gift Card、美国信用卡

>迁移后部分问题
>- 美国等一些区域转区时一定要使用对应区域的信用卡，建议选择加拿大。
>- 有订阅服务时转区可能受到障碍，特别是 Apple Music 可能需要联系人工客服解决。
>- 账户有余额时不能转区，小金额可以联系人工客服直接清零。
>- 如果转换账号区域后继续使用，可能遇到这些问题
>  1. 已经购买的项目不显示在已购项目中，搜索结果里也显示为未购买状态，需要尝试购买一次才能正常（如果记错了其实没买过会导致意外购买）
>  2. 部分应用 iAP 可能异常
>  3. 家庭共享可能异常
>  4. 恢复 iCloud/ iTunes 备份时，App 下载可能异常
>@Blankwonder


### 迁移基础

- 双币、外币信用卡VISA MasterCard均可
- 科学上网(保证操作顺畅)

## 迁移步骤

### 迁移前

#### 国区相关设置
1. 关闭家庭共享
    - 设置-第一个(Apple ID设置)-家庭共享-停止家庭共享
2. App Store 清除账户余额
    - 余额导致无法更换国家
    - 花掉或联系客服转移
3. 取消Apple Music订阅

#### 美区资料设置
1. 准备美国手机号码

- Google Voice
  - 没申请成功
  - X宝有卖的
- TextNow
  - 不清楚账号是否会保留
  - 接收Paypal短信为乱码(可能我Paypal账户的语言是中文，不支持中文短信)
- 叮咚(Dingtone)电话App
  - 每年号码保留为10元
  - 目前使用正常
2. 准备美国身份资料

- [www.fakenamegenerator.com](www.fakenamegenerator.com)
  - 据说最好生成一个美国免税州的，后续购买App可以免消费税
    - 俄勒冈Oregon
    - 阿拉斯加Alaska
    - 德拉维Delaware
    - 蒙塔娜Montana
    - 新罕布什尔New Hampshire
  - 记录好信息，以后可以反复用

3. 准备美国PayPal
- 注册
  - 注册时注意选美区的
  - 地址、验证用生成的
    - 姓名用自己的拼音
    - 手机号用之前准备的电话，要验证
  - 绑定信用卡
    - 目前一些卡不支持，个人测试的有招行EMV全球卡
    - 个人使用的中信钛金卡
    - 账单地址就是生成的美区地址
  - *据说绑定之后可以先在别的网站消费一下啥的提高账号权重，避免绑定苹果后直接消费被拒绝*

 4. *美国虚拟信用卡*

 - 目前了解到的美国虚拟信用卡有在线服务商，收费不同(有的开卡收费，有的有年费)，未做深入了解
   - [美国十大虚拟信用卡(软文)](http://www.listsandyou.com/10-best-virtual-credit-card-vcc-providers/)

### 迁移&迁移后

#### App Store迁移
- AppStore-我的账户-国家-更换国家-美国
- 输入之前准备的地址信息、自己的名字、PayPal账户，自己准备的手机注册号
  - (**如果未出现PayPal选项多半是因为没有取消家庭共享**)
  - 输入PayPal后会跳转Paypal验证

#### 应用恢复
- 需要删除掉应用，AppStore搜索应用再次购买，提示无需花钱既可购买
- 会存在显示Bug:以后删除后再下载依然显示需要购买(待解决)

#### 其他
整个过程中并未全程使用科学上网，因此完美主义者无需纠结

Tags: AppleID, 迁移美区
