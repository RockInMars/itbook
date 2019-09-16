# 布局

### 1 理解布局

##### 1.1 布局原则

​	**wpf窗口只能包含单个元素，单一窗口放置一个容器，将其它元素放置在该容器之中。**

​	**窗口原则**

- 不应显示设定元素的尺寸
- 不应使用屏幕坐标指定元素的位置
- 布局容器的子元素“共享”可用空间
- 可嵌套的布局容器

##### 1.2 布局过程

- 测量阶段，容器遍历所有子元素，并获取它们期望尺寸
- 排列阶段，容器在合适的位置放置子元素
- 布局容器不能提供认可滚动支持，滚动有其他控件实现

##### 1.3布局容器

#### 2 使用stackpanel布局

##### 2.1 布局属性

##### 2.2 对齐方式

##### 2.3 边距

​	margin=“left,up,right,down"

##### 2.4最小尺寸、最大尺寸、以及显示地设置尺寸

- 最小尺寸 控件尺寸不能小于最小尺寸
- 最大尺寸 控件尺寸不能大于最大尺寸
- 内容 如果内容需要更大尺寸，该控件将获取最小尺寸或内容尺寸中的较大尺寸
- 容器尺寸 如果容器内控件尺寸大于容器尺寸，空间尺寸将被裁剪

##### 2.5 border控件

只能包含一段嵌套内容--布局面板，为其添加背景或边框

- background 设置边框中所有内容后面的背景
- borderbrush和borderthickness 边缘边框的原色，设置边框的宽度，显示边框必须设置这两个属性
- cornerradius 圆角属性设置
- padding

#### 3 wrappanel和dockpanel

#### 4 grid

- grid.showgidlines=true 显示布局网格
- grid.row和grid.column设置行列个数
- columndefinition和rowdefinition设置行列属性
- uselayoutrounding=true 布局舍入防止布局边界模糊
- rowspan和columnspan 跨越行列
- gridsplitter 分割窗口
- sharedsizegroup共享尺寸组

#### 5 canvas













