# 智能博物馆
- 发布时间：2019年12月6日
- 项目名称：智能博物馆产品
- 项目设计者：林泽伟
# 价值主张设计
## 加值宣言
- 通过百度人体检测和属性识别API与人流量检测API，检测游客的身体关键点，查看用户是否为肢体上的残障人士，智能推荐浏览博物馆路线，尽量避免人流密集处
- 通过百度人流量检测API，为用户推荐更加舒适的观光路线
- 通过百度危险行为API，针对5s内的监控视频片段，查看是否有存在砸东西打架等行为
## 核心价值
- 帮助残障人士避开多人的浏览地点，减少被他人或者多动症患者或者好动的小孩子，无意碰撞的概率，提供更加舒适的观光体验，通过危险行为检测更好的保护博物馆内的展物与参观博物馆的人员
核心价值与用户痛点 
- 在博物馆参观是，检查会出现某些展区人流拥挤，某些展区却没人的情况，十分影响浏览体验；
- 在人流较多区域，检查会出现人与人之间无意的碰撞，或者说调皮的小孩子或者多动症患者到处捣乱的情况，这对其他参观人员或者是残障人士十分不利，需要为他们推荐避免与他们接触的路线；
博物馆内需要舒适的参观环境，需要对危险的行为进行检查

## 人工智能概率性与用户痛点
危险行为检测API当前接口仅适用于单人、双人场景，多人场景的图片，识别效果欠佳，可能会识别成双人场景。
游客着装遮挡肢体可能导致检查出现错误

 


 

## 需求列表与人工智能API加值
- 需求：需要避开儿童与多动症患者的人员
 - API百度人体检测和属性识别API与人流量检测API
- 需求：调整人流去向，更好利用博物馆资源
 - API: 人流量检测API
- 需求：防止打架，破坏展物的情况出现
 - API：危险行为检测API
 
 ## 产品原型
 - ![原型](https://github.com/Hinata013/api/blob/master/qqqq.png)
 - ![原型](https://github.com/Hinata013/api/blob/master/2222.png)
 - ![原型](https://github.com/Hinata013/api/blob/master/3333.png)
 - ![原型](https://github.com/Hinata013/api/blob/master/4444.png)
 - ![原型](https://github.com/Hinata013/api/blob/master/5555.png)
 
 

