01-微信二次修改title

02-抓包工具
fiddler2+ Rosin + Willow -->移动端开发
  Rosin可以直接打印出log
  willow 可以直接替换本地文件，以及修改host
    如果需要深研的话，可以尝试使用wireshark

03-tap点击穿透问题
方案一：fastclick.js

方案二：用touchend代替tap事件并阻止掉touchend的默认行为preventDefault()

方案三：延迟一定的时间(300ms+)来处理事件

04-记一次闪屏的问题
    场景：点击一个toggle的效果，会出现闪屏的情况，体验很不好

05-setTimeout续集
    setTimeout调用的函数被执行时的上下文是全局，而不再是调用setTimeout方法时的上下文。
    所以，setTimeout的第一个参数的函数被执行时其this是指向window的，
    如果需要保留调用setTimeout方法时的this，就需要把当时的this传进去。
    
    运行机制:setTimeout(f,0)

    异步问题的思考

06.判断文本是不是超过一行
    场景：当文本框超过一行，就显示向下的箭头或者某种样式
   
07.忘记本地数据库密码的问题 windows 操纵步骤
    
08.页面内容不缓存

09.Function.prototype.apply.call(log, console, arguments); 

10.$.ajax回调一致会报错
     
11.js命名空间学习（避免冲突、闭包、匿名函数）
   
12.字符串常用的几个函数
   
13.关于短视频问题的汇总
问题：h5 video 的 control 有些自动消失，有些不消失。

问题：h5 video 有些有全屏按钮，有些没有。有全屏按钮的点击却没有效果。

问题：Android视频不能自动播放

问题：h5 video 有可能出现黑屏（或静止图片），但有声音。

问题：h5 video有些需要点击2次才能播放。


14.页面劫持问题报到
    1）紧急解决方案
    2）修改载入的方法进行对劫持的免疫

15.关于闭包的解释
    1). 闭包更多作用
    2). 闭包与内存管理

   
16.iframe+document.domain

17.FP JS 范式

18.递归 尾递归 栈
