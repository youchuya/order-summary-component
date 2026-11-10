# Order summary card

Frontend Mentor 挑战（Newbie），纯 HTML + CSS。

- [Live site](https://youchuya.github.io/order-summary-component/)
- [Challenge](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)

## 学到什么

- `body` 用 `display: grid` + `place-items: center` 让卡片居中
- 卡片三层结构：`.card`（白底圆角裁切）→ 插画（贴边）+ 内容区（padding 48）
- `padding` 与 `margin` 的区别：多个子元素要缩进 → 加在父级
- 本地字体三档字重（Red Hat Display 500/700/900）
- CSS 变量管理颜色（规范没给白色，自己补 `--white`）
- 按钮用「同色相 + 提亮度」做 hover，不用 `opacity`（否则白字发灰）

## 响应式

- 桌面：卡片 450px，内容区 padding 48
- 手机（≤600px）：内容区 padding 24，h1 28 → 22px，背景换 mobile 版 SVG
