# grid

[codepen - demo](https://codepen.io/GivenCui/pen/QXOKXO?editors=1100)
[demo](../code/css/grid/index.html)
## 概念
- `fr` 格子之间的宽(高)把可用空间按比例分配的单位
- `Grid Lines` 格子的线, 用来定位一个item放置的`轨道 (tracks)`, 按照书写顺序, 从上到下, 从左到右, 从1开始一一对应
  - `grid-column-start`
  - `grid-column-end`
  - `grid-row-start`
  - `grid-row-end`
- `Grid Cell` grid布局中的最小单元, 4条线之间的区域

## 属性
### grid container上的属性
`grid-auto-rows` 行数自适应, 并设置每行高度
```css
.wrapper {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  grid-auto-rows: 100px;  // 行数自适应
}

```
