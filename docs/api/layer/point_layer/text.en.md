---
title: Label
order: 4
---

为图层添加文本标注

## 使用

地图标注需要添加一个新的图层的实现

### shape

- field 标注的字段名称
- shapeType 'text'

```javascript
layer.shape('name', 'text');
```

### color

同 layer

### size

同 layer

### style

- opacity `number`
- textAnchor `string` 文本相对锚点的位置 center|left|right|top|bottom|top-left
- spacing: `number` 文本包围盒 padding [水平，垂直]，影响碰撞检测结果，避免相邻文本靠的太近
- padding: `[number, number]` 文本相对锚点的偏移量 [x, y]
- stroke: `string`; 描边颜色
- strokeWidth `number` 描边宽度
- strokeOpacity `number` 描边透明度
- fontWeight `string` 字体粗细
- fontFamily `string` 字号
- textOffset `[number, number]` 文本偏移量
- textAllowOverlap: `boolean` 是否允许文字遮盖

## 相关 demo

[文本标注](../../../../examples/point/text)

`markdown:docs/common/layer/base.md`
