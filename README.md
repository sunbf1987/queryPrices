# queryPrices
##轮询京东某款商品价格

###通过jd商品价格接口，利用jsonp跨域获取相应产品价格 https://p.3.cn/prices/mgets?skuIds='J_（num）'&type=1'

###skuIds='J_（num）'中的（num）请到相应商品页面审查元素价格标签，例如：<span class="price J-p-3726832">3999.00</span>，其中J-p-3726832中的3726832即为商品价格id

###利用HTML5新增API[Notification]添加浏览器右下角通知功能，当商品价格达到预期价格，即通知并播放音乐。请使用chrome等现代浏览器浏览此页面，第一次打开页面会请求授权，请选择允许。如在本地预览，请自行安装启用本地环境。


###代码比较简单，个人娱乐。
