# Window对象
window对象是客户端JavaScript程序的全局对象。
Window对象是以窗口命名的。

## 14.1 计时器
- setTimeout()方法用来实现一个函数在指定的毫秒数之后运行
- setInterval()用法同setTimeout(),但这个函数会在指定毫秒数的间隔里重复调用：
  - `setInterval(updateClock, 60000); //每60秒调用一次updateClock()`
> 以上函数都会返回一个值，该值可以传递给clearTimeout()用于取消函数的执行


