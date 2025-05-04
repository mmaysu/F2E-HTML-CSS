## 🎃標籤生成

- ul>li

```
<ul>
   <li></li>
</ul>
```

- h1.item

```
<h1 class="item"></h1>
```

- #item

```
<div id="item"></div>
```

- ul>li#item-$*4

```
<ul>
		<li id="item-1"></li>
		<li id="item-2"></li>
		<li id="item-3"></li>
		<li id="item-4"></li>
</ul>
```

## 🎃box-sizing

![image](https://hackmd.io/_uploads/ByhrVqExxx.png)


## 🎃屬性選取器

### 1. `[attr]`

選擇包含指定屬性的所有元素，不論該屬性值是什麼。

```css
a[target] {
  color: red;
}
```

這會選擇所有具有 `target` 屬性的 `<a>` 元素，並將文字顏色設為紅色。

### 2. `[attr="value"]`

選擇具有指定屬性和值的元素。

```css
a[href="https://www.example.com"] {
  text-decoration: underline;
}
```

這會選擇 `href` 屬性值為 `https://www.example.com` 的所有 `<a>` 元素，並將其文本設為帶下劃線。

### 3. `[attr~="value"]`

選擇屬性值包含指定單詞（以空格分隔）的所有元素。

```css
div[class~="highlight"] {
  background-color: yellow;
}
```

這會選擇所有 `class` 屬性值中包含 `highlight` 單詞的 `<div>` 元素，並將其背景設為黃色。

### 4. `[attr|="value"]`

選擇屬性值為指定值或以指定值開頭並後跟連字符（`-`）的所有元素。這通常用於選擇語言屬性（如 `lang`）。

```css
html[lang|="en"] {
  font-family: Arial, sans-serif;
}
```

這會選擇 `lang` 屬性值以 `en` 開頭的所有元素（例如 `en-US`, `en-GB`），並將字體設置為 Arial。

### 5. `[attr^="value"]`

選擇屬性值以指定字符串開頭的所有元素。

```css
a[href^="https://"] {
  color: green;
}
```

這會選擇 `href` 屬性以 `https://` 開頭的所有 `<a>` 元素，並將其顏色設為綠色。

### 6. `[attr$="value"]`

選擇屬性值以指定字符串結尾的所有元素。

```css
img[src$=".jpg"] {
  border: 2px solid black;
}
```

這會選擇所有 `src` 屬性以 `.jpg` 結尾的 `<img>` 元素，並將其邊框設置為 2px 寬的黑色邊框。

### 7. `[attr*="value"]`

選擇屬性值包含指定子字符串的所有元素。

```css
a[href*="example"] {
  color: blue;
}
```

這會選擇 `href` 屬性值中包含 `example` 的所有 `<a>` 元素，並將它們的文字顏色設為藍色。

## 🎃其他

網頁檢查快捷鍵 選取： Control + Shift + C 

**冷知識：** 在html中輸入&lt xxx &gt，網頁上會呈現< xxx >

## 🎃參考資料
- 外掛：[Tailwind CSS](https://tailwindcss.com/docs/installation/using-vite)
- 插件：[css-loaders](https://css-loaders.com/)
- icon素材：[fontawesome](https://fontawesome.com/)  [CDN](https://cdnjs.com/libraries/font-awesome)
- 適合練習切版的網站：[eztravel](https://www.eztravel.com.tw/)
- 複製[三角形](https://bennettfeely.com/clippy/)
