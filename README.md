# Mon-UI

## 一套 React UI组件库 [进入文档](https://sansui-d.github.io/Tue-UI/)

![mon](https://github.com/sansui-d/Mon-UI/assets/71920152/a7903e8f-9a3e-4f43-8f37-54b7c6e47037)

> 本组件库仅供学习交流，请勿在生产环境中使用

## 安装

```
$ npm install Mon-UI
$ yarn add Mon-UI
```

## 使用

```javascript
import * as React from 'react'
import * as ReactDOM from 'react-dom'
import { Button } from 'Mon-UI'
import 'Mon-UI/lib/Mon-UI.css'

ReactDOM.render(
  <div>
    <Button>Default</Button>
  </div>,
  mountNode
)
```

需要注意的是，样式文件需要单独引入。

## 特别提醒

使用 Mon-UI 时，需要使用 border-box 盒模型，否则会影响样式。代码示例：

```css
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```
