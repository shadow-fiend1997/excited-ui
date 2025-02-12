# Button 按钮
常用操作按钮

## 基础用法

基础的函数用法

 <div style="margin-bottom:20px;">
  <ExButton color="blue">主要按钮</ExButton>
  <ExButton color="green">绿色按钮</ExButton>
  <ExButton color="gray">灰色按钮</ExButton>
  <ExButton color="yellow">黄色按钮</ExButton>
  <ExButton color="red">红色按钮</ExButton>
 </div>
 <div style="margin-bottom:20px;">
  <ExButton size="small" plain>小按钮</ExButton>
  <ExButton size="medium" plain>中按钮</ExButton>
  <ExButton size="large" plain>大按钮</ExButton>
 </div>
 <div style="margin-bottom:20px;">
  <ExButton color="blue" round plain icon="search">搜索按钮</ExButton>
  <ExButton color="green" round plain icon="edit">编辑按钮</ExButton>
  <ExButton color="gray" round plain icon="check">成功按钮</ExButton>
  <ExButton color="yellow" round plain icon="message">提示按钮</ExButton>
  <ExButton color="red" round plain icon="delete">删除按钮</ExButton>
 </div>

:::details 使用`size`、`color`、`pain`、`round`属性来定义 ExButton 的样式。

```vue
<template>
 <div style="margin-bottom:20px;">
  <ExButton color="blue">主要按钮</ExButton>
  <ExButton color="green">绿色按钮</ExButton>
  <ExButton color="gray">灰色按钮</ExButton>
  <ExButton color="yellow">黄色按钮</ExButton>
  <ExButton color="red">红色按钮</ExButton>
 </div>
 <div style="margin-bottom:20px;"
 >
  <ExButton color="blue" plain>朴素按钮</ExButton>
  <ExButton color="green" plain>绿色按钮</ExButton>
  <ExButton color="gray" plain>灰色按钮</ExButton>
  <ExButton color="yellow" plain>黄色按钮</ExButton>
  <ExButton color="red" plain>红色按钮</ExButton>
 </div>
 <div style="margin-bottom:20px;">
  <ExButton size="small" plain>小按钮</ExButton>
  <ExButton size="medium" plain>中按钮</ExButton>
  <ExButton size="large" plain>大按钮</ExButton>
 </div>
 <div style="margin-bottom:20px;">
  <ExButton color="blue" round plain icon="search">搜索按钮</ExButton>
  <ExButton color="green" round plain icon="edit">编辑按钮</ExButton>
  <ExButton color="gray" round plain icon="check">成功按钮</ExButton>
  <ExButton color="yellow" round plain icon="message">提示按钮</ExButton>
  <ExButton color="red" round plain icon="delete">删除按钮</ExButton>
 </div>
 <div style="margin-bottom:20px;">
  <ExButton color="blue" round plain icon="search"></ExButton>
  <ExButton color="green" round plain icon="edit"></ExButton>
  <ExButton color="gray" round plain icon="check"></ExButton>
  <ExButton color="yellow" round plain icon="message"></ExButton>
  <ExButton color="red" round plain icon="delete"></ExButton>
 </div>
</template>
```
:::

## 图标按钮

带图标的按钮可增强辨识度（有文字）或节省空间（无文字）。

 <div class="flex flex-row">
  <ExButton icon="edit" plain></ExButton>
  <ExButton icon="delete" plain></ExButton>
  <ExButton icon="share" plain></ExButton>
  <ExButton round plain icon="search">搜索</ExButton>
 </div>


:::details 设置 icon 属性即可，icon 的列表可以参考 Element 的 icon 组件，也可以设置在文字右边的 icon ，只要使用 i 标签即可，可以使用自定义图标。

```vue
<template>
 <div class="flex flex-row">
  <ExButton icon="edit" plain></ExButton>
  <ExButton icon="delete" plain></ExButton>
  <ExButton icon="share" plain></ExButton>
  <ExButton round plain icon="search">搜索</ExButton>
 </div>
</template>
```