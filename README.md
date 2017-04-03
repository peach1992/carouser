API:
$(selector).slider(options,callback(api));
options  default:
contentCls	'content'	轮播内容列表的class
navCls	'nav'	轮播导航列表的class
prevBtnCls	'prev'	向前一步的class
nextBtnCls	'next'	向后一步的class
activeTriggerCls	'active'	导航选中时的class
disableBtnCls	'disable'	按键不可用时的class
hoverCls	'hover'	当鼠标移至相应区域时获得的class
steps	1	移动帧数,'auto'为自动调整
direction	'x'	轮播的方向
reverse	false	是否反向自动播放
inEndEffect	'switch'	播放到最后一帧时的效果："switch"表示来回切换,"cycle"表示循环,"none"表示无效果
hasTriggers	true	是否含有导航触发点
triggerCondition	'*'	触发点的条件(有时需排除一些节点)
triggerType	'mouse'	导航触发事件类型:"mouse"表鼠标移入时触发,"click"表示鼠标点击时触发
activeIndex	0	默认选中帧的索引
pointerType	'click'	左右箭头的触发事件类型:"mouse"表鼠标移入时触发,"click"表示鼠标点击时触发
auto	false	是否自动播放
animate	true	是否使用动画滑动
delay	3000	自动播放时停顿的时间间隔
immediately	false	悬浮是否立即停止
duration	500	轮播的动画时长
easing	'easeIn'	切换时的动画效果,可选的动画函数包括:swing,easeIn,easeOut,expoin,expoout,expoinout,elasin,elasout,elasinout,backin,backout,backinout,bouncein,bounceout,bounceinout
keyboardAble	false	是否允许键盘按键控制
touchable	true	是否允许触碰
sensitivity	0.4	触摸屏的敏感度,滑动当前帧的百分比移动该帧，该值越小越敏感
scrollable	false	是否允许滚动滚动轴时换屏
beforeEvent(status)	[无]	移动前执行,返回flase时不移动;传入一个对象,包含：index事件发生前索引,count帧长度,destination方向(prev向前,next向后,数字为相应的索引),event事件对象;
afterEvent(status)	[无]	移动后执行;传入一个对象,包含：index事件发生前索引,count帧长度,destination方向(prev向前,next向后,数字为相应的索引),event事件对象

callback:
prev()	向前一步
next()	向后一步
start()	开始播放
stop()	停止播放
resize()	重置幻灯片参数
setIndex(index,isAnimate)	设置当前帧
setSteps(steps)	设置移动帧数
setDelay(delay)	设置动画停顿时间间隔
setDuration(duration)	设置动画时长
getIndex()	获取当前帧
getSize()	获取帧数
getOptions()	获取组件当前参数值

