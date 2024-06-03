# *扫码点餐微信小程序*

[TOC]

### 介绍：

扫码点餐该程序为微信小程序在线点餐与在线预约小程序，适用于所有餐厅以及餐馆。

本程序分为三个角色：超管、职工、普通用户。并且将管理端也放在小程序上，超管和职工可在小程序上操作一切功能。

接下来我将讲解一下三个角色分别有什么功能？

普通用户：

- 在线点餐
- 在线预约
- 在线付款

职工：

- 普通用户的所有功能

- 包厢预约
- 菜品库存管理（可设置库存数量）
- 打印机连接
- 下单管理（可查看现场扫码下单和预约情况 可打印菜单 确认到场 取消预约）
- 在线点餐（帮助用户下单）
- 餐桌管理（可结算该餐桌订单 删除订单 设置上菜情况）
- 仓库管理（独立的库存 可记录进出货情况）

超管：

- 职工的所有功能
- 菜单设置
- 菜单分类设置
- 餐桌设置（可生成餐桌二维码）
- 营业额
- 角色管理

### 后续及作者联系：

​	因存在商业性，本程序不免费分享。如果想要进一步了解或者体验该程序，请于我取得联系（**微信：tarihs  QQ:480549916**）备注来意

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/my/wximage.png)

## 一、主要功能：

- [x] 扫码点餐
- [x] 用户在线付款
- [x] 在线预约（可多次预约）
- [x] 取消预约（职工权限）
- [x] 在线预约+预约点餐
- [x] 菜品多计价模式（按斤、按数量、按份）
- [x] 菜品可在多个分类中
- [x] 可分包厢与大厅桌
- [x] 可设置菜品库存（无库存自动显示售空）
- [x] 可设置上菜状态
- [x] 可用蓝牙打印机打印菜单
- [x] 可查看营业额（有统计菜品出售情况）
- [x] 用户点餐时共享菜单
- [x] 可设置菜单以及菜单分类显示优先级
- [x] 角色管理
- [x] 独立库存系统（可用于记录进出货）
- [x] 职工可直接结账
- [x] 职工可删除订单
- [x] 可生成餐桌码
- [ ] 分店
- [ ] 优惠卷

## 二、开发介绍

- 前端：uniapp
- 后端：springboot

## 三、在线体验小程序

提示：

1. 因为要给你们体验各种权限(默认超管权限)，所以开了个体验版小程序，由于微信限制所以需要通过申请才可以体验，我收到申请会第一时间通过，有其他问题请留言给我或添加我的联系方式。

2. 因为在线点餐共享菜单只存在于普通用户之间，职工和超管身份也不需要共享菜单，如果需要体验请自行改身份为**普通用户**

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/ouE-N68irFtGfgtmTuzEVXnI5tZs.jpg)

## 四、部分界面截图

#### 1.首页

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240603234342438.png)

#### 2.点餐页面

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/22.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/23.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/24.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527013057878.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527013118680.png)


#### 3.买单界面

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527013404283.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527013501780.png)

#### 4.我的界面

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240603235519455.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240603235444099.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240603235402550.png)

#### 用户预约界面：

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527014852040.png)

#### 预约大厅：

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527014916125.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527014924779.png)

#### 预约包厢：

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240527015004647.png)


![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240603234933378.png)

![输入图片说明](https://gitee.com/lotian999/Scan-QR-code-to-order-food/raw/master/online/images/image-20240603235058872.png)
