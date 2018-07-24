
### 先实现简单轮播 Simple
> 点击切换，不点击不切换

实现方法：
1.点击哪张，哪张visiblity为visible（默认除第一张，其余为visiblity为hidden），区域为hidden

### 再实现纯定时器轮播 semi-auto
1. 点击无交互，纯按时间自己滚动

### 最终两者融合，实现正常轮播 auto
1. 点击时跳转，不点击时按定时器跳转


### dest中文件解释
1. c1是指第一种的轮播图，点击下方的小的缩略图，展示大图，并通过定时器进行切换
2. c2是指第二种的轮播图，点击下方小点或者左右箭头，都可以实现切换，当不进行操作时，可通过定时器进行切换
3. c3是指第三种轮播图，点击下方小点或者左右箭头进行切换，与第二种轮播区别是第三种轮播有3d效果