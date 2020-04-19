# 第二週版型攻略

<br>

## Emmet 常用紀錄

Flex

- `df`
- - `display: flex;`
- `fxdc`
- - `flex-direction: column;`
- `jcc`
- - `justify-content: center;`
- `jcsb`
- - `justify-content: space-between;`
- `aic`
- - `align-items: center;`

<br>

一般

- `bg`
- - `background: #000;`
- `bous`
- - `border-radius`
- `c`
- - `color: #000;`
- `fw`
- - `font-weight`
- `fz`
- - `font-size`
- `fsi`
- - `font-style: italic;`
- `lh`
- - `line-height`
- `maw`
- - `max-width`
- `po`
- - `position: relative;`
- `poa`
- - `position: absolute;`
- `tac`
- - `text-align: center;`

<br>

## CSS Backgrounds

[background_shorthand](https://www.w3schools.com/css/css_background_shorthand.asp)

- background-color
- background-image
- background-repeat
- background-attachment
- background-position

<br>

## Flex 小知識

[flex-wrap: wrap;](https://codepen.io/hedgehogkucc/pen/vYNKxOE?editors=1100)

<br>

## Code Review

洧杰老師建議：

- .header 部分請不要用 margin 與 padding 來推擠，一種做法是可試著寫死一個高度，並用 flex 垂直置中
- d-flex 運用得不錯
- 圖片推擠你直接在 img style 下了 margin-left: 24px;，這段請寫在 CSS 上，不要寫在 HTML 標籤
- .otherWorks li:first-child, .otherWorks li:nth-child(4) 的做法蠻有趣的，但要留意如果網站裡面變動率很高，則建議不要這麼寫
- 有嘗試使用小駝峰命名，這點很不錯
- 子模組命名也 ok，例如 about、about_profile
- .container 運用得很棒

你 Flex 運用得蠻好的，再次恭喜過關 :D