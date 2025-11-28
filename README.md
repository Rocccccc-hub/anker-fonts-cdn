# Anker Fonts CDN

Mont For Anker 企业字体 CDN 资源库

## 快速使用

### 方法 1: 通过 link 标签引入

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Rocccccc-hub/anker-fonts-cdn/mont-for-anker.css">
```

### 方法 2: 在 CSS 中使用 @import

```css
@import url('https://cdn.jsdelivr.net/gh/Rocccccc-hub/anker-fonts-cdn/mont-for-anker.css');
```

### 应用字体

```css
body {
  font-family: 'Mont For Anker', -apple-system, BlinkMacSystemFont, sans-serif;
}

/* 使用不同字重 */
.light { font-weight: 300; }     /* Book */
.regular { font-weight: 400; }   /* Regular */
.semibold { font-weight: 600; }  /* SemiBold */
.bold { font-weight: 700; }      /* Bold */
.heavy { font-weight: 900; }     /* Heavy */
```

## 字体列表

| 字体文件 | 字重 | 格式 |
|---------|------|------|
| MontForAnker-Book | 300 | WOFF2, WOFF |
| MontForAnker-Regular | 400 | WOFF2, WOFF |
| MontForAnker-SemiBold | 600 | WOFF2, WOFF |
| MontForAnker-Bold | 700 | WOFF2, WOFF |
| MontForAnker-Heavy | 900 | WOFF2, WOFF |

## 在 Figma 导出的网页中使用

在导出的 HTML 文件的 `<head>` 标签中添加：

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Rocccccc-hub/anker-fonts-cdn/mont-for-anker.css">
```

然后在 CSS 中应用：

```css
* {
  font-family: 'Mont For Anker', sans-serif;
}
```

## 许可证

此字体为 Anker 企业专用字体，仅供内部使用。
