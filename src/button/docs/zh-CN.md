# 按钮

### 介绍

按钮组件，用于触发操作

### 基本使用
```html
<lc-button>基本使用</lc-button>
```

### 主题色按钮
```html
<template>
  <lc-button type="primary">主要按钮</lc-button>
  <lc-button type="info">信息按钮</lc-button>
  <lc-button type="success">成功按钮</lc-button>
  <lc-button type="warning">警告按钮</lc-button>
  <lc-button type="danger">危险按钮</lc-button>
</template>
```

## API

### 属性

| 参数 | 说明 | 类型 | 默认值 | 
| --- | --- | --- | --- | 
| `color` | 按钮颜色 | _string_ | `default` |

### 事件

| 事件名 | 说明 | 参数 |
| --- | --- | --- |
| `click` | 点击按钮时触发 | `event: Event` |

### 插槽

| 插槽名 | 说明 | 参数 |
| --- | --- | --- |
| `default` | 按钮内容 | `-` |