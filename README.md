# NFT Market #
<a name="N0MqR"></a>
### 发行一个NFT
![图片.png](https://cdn.nlark.com/yuque/0/2024/png/27181615/1705385888848-d57db043-fb89-477c-8bd0-e167added6f8.png#averageHue=%23232538&clientId=uea983b3e-1d47-4&from=paste&height=335&id=u8f43a589&originHeight=502&originWidth=844&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=41512&status=done&style=none&taskId=ue410964d-a200-42a9-a89f-784d421bb3e&title=&width=562.6666666666666)<br />mint()后在opensea上查看
<a name="Mx0XJ"></a>
### ![图片.png](https://cdn.nlark.com/yuque/0/2024/png/27181615/1705385976049-a7a86951-80c2-4955-b234-4c340c08b73a.png#averageHue=%23e0bfb5&clientId=uea983b3e-1d47-4&from=paste&height=480&id=uc238d39e&originHeight=720&originWidth=1362&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=900201&status=done&style=none&taskId=uc877f513-721f-48ac-8b99-a169b2d802a&title=&width=908)
<a name="b9KfL"></a>
### 编写一个Market合约:
<a name="PUaGy"></a>
#### 1.使用自己发行的ERC20 Token 来买卖NFT
![图片.png](https://cdn.nlark.com/yuque/0/2024/png/27181615/1705386089373-91721cd7-a36f-445a-b3ab-b4ad8d4eddec.png#averageHue=%2324273b&clientId=uea983b3e-1d47-4&from=paste&height=43&id=ua23f6003&originHeight=64&originWidth=977&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=21621&status=done&style=none&taskId=u74465e1e-4e0f-4018-a755-ca09c0f3955&title=&width=651.3333333333334)
<a name="rRCov"></a>
#### 2.NFT 持有者可上架 NFT(设置价格多少个TOKEN可以购买 NFT )
![图片.png](https://cdn.nlark.com/yuque/0/2024/png/27181615/1705386163838-8c597d43-cf28-4390-b276-cc3249de912a.png#averageHue=%2325273a&clientId=uea983b3e-1d47-4&from=paste&height=191&id=ue5b3a4aa&originHeight=287&originWidth=720&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=26441&status=done&style=none&taskId=uf2cb4476-a4dd-49d5-b183-8dd04603a7a&title=&width=480)
<a name="qDVEH"></a>
#### 3.编写购买NFT 方法 buyNFT(uint tokenID, uint amount),转入对应的TOKEN,获取对应的 NFT
![图片.png](https://cdn.nlark.com/yuque/0/2024/png/27181615/1705386227507-65066f63-374e-4b6d-8a8c-f76929799b07.png#averageHue=%23282a3e&clientId=uea983b3e-1d47-4&from=paste&height=151&id=u98bf7f74&originHeight=226&originWidth=869&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=39972&status=done&style=none&taskId=u7f9bb0ad-e16c-4a8a-a346-c967a34cce7&title=&width=579.3333333333334)<br />sells[tokenID] = false;//下架
