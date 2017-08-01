#### 1. animation-name	
* 规定 @keyframes 动画的名称

#### 2.@keyframes
````css
    @keyframes mymove
    {
        0%   {top:0;}
        25%  {top:200px;}
        50%  {top:100px;}
        75%  {top:200px;}
        100% {top:0;}
    }
````

#### 3.animation-duration	
* 规定动画完成一个周期所花费的秒或毫秒。默认是 0

#### 4.animation-timing-function	
* 规定动画的速度曲线，默认是 "ease"，和 transition-timing-function 同理

#### 5.animation-delay	
* 规定动画何时开始，默认是 0

#### 6.animation-iteration-count	
* 规定动画被播放的次数，默认是 1

#### 7.animation-direction	
* 规定动画是否在下一周期逆向地播放，默认是 "normal"
    * normal	        正常播放。
    * alternate	        动画应该轮流反向播放。

#### 8.animation-play-state	
* 规定动画是否正在运行或暂停，默认是 "running"
    * running	规定动画正在播放。
    * paused	规定动画已暂停。

#### 9.animation-fill-mode	
* 规定对象动画时间之外的状态。
    * none	        不改变默认行为。
    * forwards	    当动画完成后，保持最后一个属性值（在最后一个关键帧中定义）。
    * backwards 	在 animation-delay 所指定的一段时间内，在动画显示之前，应用开始属性值（在第一个关键帧中定义）。
    * both	        向前和向后填充模式都被应用。

#### 10.animation	
* 所有动画属性的简写属性，除了 animation-play-state 属性