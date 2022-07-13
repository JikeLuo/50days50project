## <var/\>

這是 `var` 標籤： <var>I am var tag, 我是 var</var>



---

## <code/\>

這是 `code` 標籤： <code>I am code tag, 我是 code</code>



---

## <u/\>

+ 此元素以前在舊版本的 `HTML` 中稱為 `“下劃線”` 元素
  + 但有時仍會以這種方式被濫用
+ 要為文本加下劃線，您應該應用包含 `CSS text-decoration` 屬性設置為 `underline` 的樣式

這是 `u` 標籤： <u>I am u tag, 我是 u</u>



---

## <cite/\>

+ 表示一个作品的引用

這是 `cite` 標籤： <cite>I am cite tag, 我是 cite</cite>



---

##  <blockquote/\>

+ 文字是引用內容。通常在渲染時，這部分的內容會有一定的縮進
+ 就是 `markdown` 的 `>`

這是 `blockquote` 標籤： 

<blockquote>I am code blockquote, 我是 blockquote</blockquote>



---

## <figure/\> & <figcaption\>

+ 引用任何內容，文字段落、圖片、圖表或程式等
+ 目的是用來包含內容 `自我獨立 self-contained` 的區塊
+  `<figcaption\>` 用來說明該 `figure` 區塊的標題

<figure>   
    <img src="https://picsum.photos/500/200">  
    <figcaption>this is figcaption</figcaption> 
</figure>



---

## <aside/\>

+ 表示此內容是跟主要內容沒直接關係的區塊
+ 作為頁面的額外資訊，可以放在 aside 中的像是網頁側邊欄資訊、廣告等

這是 `aside` 標籤： 

<aside>I am cite aside, 我是 aside</aside>



---

## <select/\> & <option/\>

+ 顯示下拉式選單
  + `option` 為選項列

```html
<select>
    <option>請選擇你最愛的寵物</option>
    <option>Dog</option>
    <option>Cat</option>
    <option>Hamster</option>
</select>
```



---

## <article/\>

+ 用來描述這一區塊的內容本身是獨立且完整的
  + 例如部落格中的一篇文章、一則留言，或像論壇中的一個回覆等

```html
<article>  
    <h2>News 1</h2>
    <p>this is article</p>
</article>
```



## crossorigin

+ 一些 HTML 元素提供對 `CORS` 的支持，均有一个跨域屬性，它允許你配置元素獲取數據的 CORS 請求。 
  + `<audio/>`
  + `<img/>`
  + `<link/>`
  + `<script/>`
  + `<video/>`

```html
<script src="https://example.com/example-framework.js" crossorigin="anonymous"></scrip
```

| 關鍵字            | 描述                                                         |
| ----------------- | ------------------------------------------------------------ |
| `anonymous`       | 此元素的 CORS 請求將不設置憑據標誌。                         |
| `use-credentials` | 此元素的 CORS 請求將設置憑證標誌；這意味着著求將提供憑據。   |
| `""`              | 一个空的值，如 `crossorigin` 或 `crossorigin=""`，和設置 `anonymous` 的效果一樣。 |



