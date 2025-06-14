### tReceiveOrder

![res](/home/wuzhanfly/git/work/data-res/res/res.png)

```json

{
  "amount": "string", 
  "czTimes": 6,
  "fromAddressPart": "string",
  "orderNo": "string",
  "toAddress": "string"
}
```

#### 参数说明：

| 参数            | 例子                               | 备注                                                         |
| :-------------- | :--------------------------------- | ------------------------------------------------------------ |
| amount          | 182.3,                             | 订单金额，订单的资产类型(USDT,TRX)程序会自动判断             |
| czTimes         | 3                                  | 0,1,2,3,5                                                    |
| fromAddressPart | TGGYKKK                            | 前三后四码,注意后续需补充密钥以及完整地址，测试时这地址权限自己要能控制 |
| orderNo         | 1633                               | 订单号(不可重复)                                             |
| toAddress       | TZEe33rWz4DpRKmEtchaeZXb9sRwj7qTtt | 目标地址，订单接受者地址同样，测试时这地址权限自己要能控制   |

#### 完整例子

````json

{
  "amount": "168.2", 
  "czTimes": 3,
  "fromAddressPart": "TGGYKKK",
  "orderNo": "1633",
  "toAddress": "TZEe33rWz4DpRKmEtchaeZXb9sRwj7qTtt"
}
````

