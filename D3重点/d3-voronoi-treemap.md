# 数据处理

## d3.hierarchy()

[d3-hierarchy/README.md at v3.1.2 · d3/d3-hierarchy (github.com)](https://github.com/d3/d3-hierarchy/blob/v3.1.2/README.md#hierarchy)

为层次结构数据生成一个根节点

在传递前需要调用sum（）

```js
hierarchy = d3.hierarchy(rootData).sum(function(d){ return d.weight; });
```

# 相关API

## d3.**voronoiTreemap**(root)

使用默认配置创建一个新的的voronoiTreemap模拟

root为数据经过d3.hierarchy()计算后生成的根节点数组（[d3.hierarchy / D3 / Observable (observablehq.com)](https://observablehq.com/@d3/d3-hierarchy)）

为节点分配切割后的多边形？

### clip()

设置要被裁剪的多边形，计算适当的范围和大小，并返回此布局

传入二维点数组，数组点的分布满足两个条件

1. 开放，不重复
2. 逆时针，原点[0,0]在左上角

默认：

```
[
  [0, 0],
  [0, 1],
  [1, 1],
  [1, 0],
];
```

