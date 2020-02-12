# 基于媒体查询的响应式布局

```$xslt
PS: 闲来无事学习一下响应式
```

- viewport
    媒体查询视图属性
    ```$xslt
    <meta name="viewport" content="width=device-width, initial-scale = 1.0, maximum-scale = 2.0 >"
    ```
- meta 属性
    规定在何种宽度上启用对应的 css 样式
    ```$xslt
    <link rel="stylesheet" meta="(min-width: 1024px)" href="./desktop.css">
    <link rel="stylesheet" meta="(max-width: 768px)" href="./mobile.css">
    ```