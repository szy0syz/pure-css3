# Pure-CSS3

## Ch1

![c01](./assets/Ch1-1.png)
![c02](./assets/Ch1-2.png)

- 杨辉三角的那个第一个和最后一个子元素的确是个 `trick`

```css
.triangle div span:first-child,
.triangle div span:last-child {
  background-color: lightcoral;
}
```

- 棋盘这个 奇偶子元素有意思

```css
.chessboard div:nth-child(odd) span:nth-child(even),
.chessboard div:nth-child(even) span:nth-child(odd) {
  background-color: rgba(0, 0, 0, 0.3);
}
```

## Ch2

![ch02-1](./assets/Ch2-1.png)
![ch02-steamer](./assets/Ch2-steamer.png)
![ch02-monster](./assets/Ch2-monster.png)

## Ch05 阴影

![ch05-calendar](./assets/ch05-calendar.png)
![ch05-window](./assets/Ch05-window.png)

## Ch06 剪切、滤镜和色彩混合

## 07 变量与计数器

![001](./assets/001.png)

- 拿4个变量给四个小矩形的4个边框分别上色
- 然后旋转45°
- 最后把超出的边框的部分透明色

![002](./assets/002.png)

- `background` 使用三重属性叠加，实现了 `a single div` 💘
- 使用 `clip-path: polygon` 对杯子整体切边，精妙 🎈
- 最后使用变量后，把复杂的结构拆分，语义化更强，代码更易读懂 ✅
