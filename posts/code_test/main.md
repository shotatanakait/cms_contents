---
Keywords: code, programming, test
Copyright: (C) 2023 Shota Tanaka
---

# Code test

## はじめに
コードの埋め込みテストを行います。

## HTML
HTMLのテストです。

```html
<!-- html -->
<div id="test1">
    <h3>HTMLのタイトル</h3>
    <p class="center">これは段落です。</p>
</div>
```




## CSS
CSSのテストです。

```css
/* css */
h3 {
  font-size: 30px;
  color: blue;
}
```

## JavaScript
JavaScriptのテストです。

```javascript
// javascript
const sampleFunc = (text) => {
  if (!text) {
    console.log("alert: arg text is undefined");
    return;
  }
  console.log(text);
}
sampleFunc("this function is called.");
```

## Bash
bash shellのテストです。

```bash
# bash
seq 1 10 | awk '{print $1, $3}'
```


## まとめ

確認は以上です。現在はデバッグおよびUI修正中です。





                   
                   
                   
                   
                   
                   
                   
                   
                   
