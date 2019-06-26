# 会员积分变动接口

## 接口关键词

shopMemberPoint

## 接口触发场景

### 积分增加触发场景

* 关注公众号送积分
* 会员卡充值返积分
* 管理员充值积分
* 签到赠送积分
* 购买返积分
* 新客有礼赠送

### 积分消减触发场景

* 积分兑换到会员卡
* 积分兑换到微信钱包
* 积分兑换到代金券
* 积分兑换到礼品券
* 退款返积分

## 接口内容

* openid，客户公众号openid
* miniAppOpenId，小程序openid
* phone，手机号
* point，积分
* action，取值add和minus，add积分增加，minus积分减少。





```text
            case 'follow': return '关注公众号送积分';
            case 'mall': return '会员卡充值返积分';
            case 'admin': return '管理员充值积分';
            case 'checkin': return '签到赠送积分';
            case 'back': return '购买返积分';
            case 'cutcard': return '积分兑换到会员卡';
            case 'cutmoney': return '积分兑换到微信钱包';
            case 'cutfavor': return '积分兑换到代金券';
            case 'cutgift': return '积分兑换到礼品券';
            case 'cutrefund': return '退款返积分';
            case 'firstMoney': return '新客有礼赠送';
```

