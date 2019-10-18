# 好货特拼
好货特拼小程序是一款为买家提供省钱购物的社交电商平台，为微信的流量主提供更有效率的变现，裂变。

因为该项目为已上线商业项目，想详细了解项目源码可加QQ:925306022

## Screenshots

![Image text](/screenshots/1.png)
![Image text](/screenshots/3.png)
![Image text](/screenshots/4.png)
![Image text](/screenshots/5.png)
![Image text](/screenshots/7.png)
![Image text](/screenshots/8.png)
![Image text](/screenshots/2.png)
![Image text](/screenshots/6.png)

## 技术要点

- 首页tab与商品筛选组件的吸顶效果
- 利用自定义Component与template制定通用的列表
- 列表一次性渲染大量数据，对列表进行上拉刷新下拉加载更多，增量、局部刷新
- 复杂的商品详情界面的样式编写，封装自定义的Button组件用于减少多个界面上的重复授权操作 
- mask遮罩组件：应用slot插槽兼容不同的弹窗样式，并阻止界面滑动穿透
- search搜索组件：同步从不同界面内参数的传递并及时更新组件的状态，并为不同的界面传递必需的参数与
- 价格区间筛选组件：选择不同的价格时，同步更新父界面的状态与列表数据，并校验好用户非常规的操作所导致的功能错误
- 商品的图文分享：长按复制分享文案；选择多张商品图片，为每一张图片进行canvas绘制上小程序码或二维码后生成海报，并批量下载保存和预览生成的海报图片

## 扫码体验
![Image text](https://github.com/BLCheung/TePinGood/blob/master/poster/poster.jpg)
