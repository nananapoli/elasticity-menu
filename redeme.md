功能
  1. 菜单栏长度的变化
  2. 中间文字的出现与消失，即旋转，透明度的变化，以及不同的延迟顺序
  3. label标签（两条小杠，伪元素）的旋转和位移

技术点
  1. input+label触发状态的改变
  2. box-sizing设置成border-box，利用padding向内固定子元素，使其居中
  3. 对width，opacity，rotate，translate等属性使用transition和transform，并且对于来回两个步骤都要设置transition，timing-funciton可相同可不同，延迟顺序也不同

tips
  ● 经典居中：绝对定位，top,left各50%，margin-top，left各负的半个元素长
  ● pointer-events可以取消元素的事件触发，input标签
  ● ul 的fontsize设为零
  ● perspective
  ● .nav-btn:hover:before 鼠标悬浮给子元素中的伪元素改样式的写法

想法
transform：起点到终点
transition：中间的过渡，变化的属性，时间，delay，timing-funciton动画运行速率


扩展
再做下拉菜单