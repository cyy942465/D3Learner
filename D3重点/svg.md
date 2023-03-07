# svg

## 绘制图形

### 矩形元素`<rect>`

- #### x,y

  - 左上角坐标值

- #### width和height

  - 矩形的宽度和高度

- #### rx和ry

  - 设置圆角矩形

### 圆形元素`<circle>`

- #### cx和cy

  - 圆心的坐标值

- ### r

  - 圆形的半径

### 椭圆元素`<ellipse>`

- #### cx和cy

  - 椭圆的圆心坐标值

- #### rx和ry

  - 水平方向和垂直方向的半径

### 线条`<line>`

- #### x1和y1

  - 起点坐标

- #### x2和y2

  - 终点坐标

### 折线`<polyline>`

- #### points

  - 点集合

### 文字`<text>`

- #### font-family

- #### font-size

### 路径`<path>`

[(49条消息) Svg Path 用法详解_SHCQMY的博客-CSDN博客_svg的path](https://blog.csdn.net/weixin_39868379/article/details/114403129?ops_request_misc=%7B%22request%5Fid%22%3A%22166607734216782428695738%22%2C%22scm%22%3A%2220140713.130102334..%22%7D&request_id=166607734216782428695738&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-114403129-null-null.142^v58^pc_rank_34_2,201^v3^control_1&utm_term=svgpath&spm=1018.2226.3001.4187)



### 分支元素g

## 文字

### `<text>`

- #### x和y

  - 文字位置的坐标

- #### dx和dy

  - 当前位置在x和y上平移的距离（正为右，负为左）

- #### textLength

  - 文字的显示长度（不足则拉长，足则压缩）

- #### rotate

  - 旋转角度（顺时针为正，逆时针为负）

## 设置样式style

### 通过元素的属性设置

#### fill

填充样式

#### fill-opacity

设置填充透明度

#### stroke

设置描边样式

#### stroke-width

设置边框的宽度

#### font-family

字体

#### font-size

字体大小

### 通过style属性

#### transform

- translate(x,y)
  - 向右平移x，向下平移y
- rotate(xdeg)
- scale
  - 缩放