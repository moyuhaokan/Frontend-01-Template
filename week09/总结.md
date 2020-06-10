

### animation

**@keyframes定义 关键帧**

- animation-name 时间曲线
- animation-duration 动画的时长
- aanimation-timing-function 动画的时间曲线
- animation-delay 动画开始前的延迟
- animation-iteration-count 动画的播放次数
- animation-direction 动画的方向

#### transition

- transition-property 要变换的属性
- transition-duration 变换的时长
- transition-timing-function 时间曲线
- transition-delay 延迟

### 贝塞尔曲线 

是一种插值曲线，描述了两个点之间差值来形成联系的曲线形状规则。



ax^2+bx+c一元二次方程 v 是速度，g 重力加速度，t 时间

### 渲染

RAB 是指红色，绿色，蓝色。

HSL 是一种语义化的颜色。HSL是一种将RGB色彩模型中的点在圆柱坐标系中的表示



### DOM 

- node

  element 元素型节点，跟标签一样

  Document 文本根节点

  CharaterData 字符数据， 包括 text,comment，ProcessingInstruction

- 导航类操作

  - parenNode 
  - childNodes
  - firstChild
  - lastChild
  - nextSibling
  - previousSibling

- 修改操作

  - appendChild
  - insertBefore
  - removeChild
  - replaceChild

- 高级操作

  - compareDocumentPosistion 是一个用于比较两个节点中关系的函数。
  - contains 检查一个节点是否包含另一个节点的函数。
  - isEqualNode 检查两个节点是否完全相同。
  - isSameNode 检查两个节点是否在同一个节点，实际上在 JavaScript 可以用====
  - cloneNode 复制一个节点，如果传入的参数 true，则会连同子元素做深拷贝。

- DOM event

  先捕获再冒泡

