jQ_prat01 <br>
[link: 2020-07-10-JQ-node01] (https://gist.github.com/bestRDJ333/c39e122ead63d136e1fc263df1cf79de)

<hr>
jQ_prat02
jQ選取器

|    |    jQ    |   CSS  |    說明  |  備註  |
|----|----------|--------|----------|-------|
| 1  | $('div') | div{}  |   |   |
| 2  | $('h1')  | h1{}  |   |   |
| 3  | $('h2')  | h2{}  |   |   |
| 4  | $('p')  |  p{} |   |   |
| 5  | $('ul')  | ul{}  |   |   |
| 6  | $('li')  | li{}  |   |   |
| 7  | $('#AAA')  | #AAA{}  |   |   |
| 8  | $('.AAA')  | .AAA{}  |   |   |
| 9  | $('div#AAA')  |  div#AAA{} |   |   |
| 10  | $('div.AAA')  | div.AAA{}  |   |   |
| 11  | $('li.AAA')  |  li.AAA{} |   |   |
| 12  | $('#AAA li')  |  #AAA li{} | 後代選取器  |   |
| 13  | $('#AAA > li') | #AAA > li{}  | 子代選取器  |   |
| 14  | $('#AAA + li') | #AAA + li{}  | 臨代選取器  |   |
| 15  | $('#AAA ~ li')  | #AAA ~ li{} | 同代選取器   |   |
| 16  | $('h1, h2, h3')  | h1, h2, h3{}  |   |   |
|   | ///   |   |   |   |
| 17  | :first-child  |   | 篩選全部第一個  |   |
| 18  | :last-child   |   |  篩選全部最後一個 |   |
| 19  | :not(.AAA)    |   | 篩選不是.AAA  |   |
| 20  | :eq(2)        |   | 篩選第三個li  |   |
| 21  | :gt(2)        |   |  篩選第三個之後的 |   |
| 22  | :lt(2)        |   | 篩選三個之前的  |   |
| 23  | :first        |   | 篩選整頁的第一個  |   |
| 24  | :last         |   |  篩選最後一個 |   |
| 25  | :even         |   | 篩選偶數的  |   |
| 26  | :odd          |   |  篩選基數的 |   |
| 27  | :visible      |   | 篩選可見的  |   |
| 28  | :hidden       |   |  篩選隱藏的 |   |
|   | ///  |   |   | ///jQ可用filter(": ")篩選  |
| 29  | $(this)       |   | 滑鼠摸到的  |   |
| 30  | $(window)     |   | 瀏覽器功能  |   |
| 31  | $(document)  |   |  網頁內容區 | 可以不用有“”  |

DOM Traversal Methods 指令
|   |  方法/指令 | 說明  |  
|---|---|---|
|  1 | .filter()  | 過濾篩選  |   
|  2 | .not()  |  除此之外 | 
|  3 | .has()  |  有後代 |   
|  4 | .eq()  | 指定第幾個  | 
|  5 | .first()  | 第一個  |   
|  6 | .last()  |  最後一個 | 
|  7 | .slice()  | 從第幾個開始  |   
|  8 | .find()  |  找指定DOM標籤 | 
|  9 | .children()  |  全部子代 |   
|  10 | .parents()  | 全部前袋  | 
|  11 | .parent()  |  單前一代 |   
|  12 | .offsetParent()  |  座標前代 | 
|  13 | .siblings()  | 所有同代兄弟  |   
|  14 | .prev()  |  前一個同代兄弟 | 
|  15 | .prevAll()  | 前面所有的同代兄弟  |   
|  16 | .next()  | 後一個同代兄弟  | 
|  17 | .nextAll() | 後面所有的同代兄弟  |   
|  18 |  .end  | 結束連結返回開頭  | 

DOM操作
|   |  方法/指令 | 說明  |  
|---|---|---|
|  1 |  .attr()       | 控制Html標籤內屬性  |   
|  2 |  .removeAttr() |  移除Html標籤內屬性 | 
|  3 | .css()         | 控制CSS屬性  |   
|  4 | .height()      | 高度  | 
|  5 | .innerHeight()  | 高度(加含padding)  |   
|  6 | .outerHeight()  | 高度(全含Ｍ，Ｐ，Ｂ)  | 
|  7 |  .width()       |  寬度 |   
|  8 | .innerWidth()  | 寬度(加含padding)  | 
|  9 | .outerWidth()  | 寬度(全含Ｍ，Ｐ，Ｂ)  |   
|  10 |  .offset()    |  以網頁文件為準的座標 | 
|  11 | .position()   |  以上一層為準的座標 |   
|  12 | .scrollTop()  | 網頁捲軸位置  | 
|  13 | .scrollLeft()  |  網頁捲軸位置 |   
|  14 |  .hasClass()  | 有 class名字的那個  | 
|  15 | .addClass()    | 增加 Class名稱  |   
|  16 | .removeClass()  |  移除 Class名稱 | 
|  17 |  .toggleClass() | Class名稱開關 |   
|  18 | .html()         | 同js的inner  | 


動畫效果
|   |  方法/指令 | 說明  |  
|---|---|---|
|  1 |  .show()    |  顯示 |   
|  2 |  .hide()    |  隱藏 | 
|  3 | .toggle()   |  切換顯示隱藏 |
|    | .slideDown()  | 往下滑移顯示  | 
|  4 |  .slideUp() |  往上滑移 | 
|  5 | .slideToggle()  | 往上滑移顯示  |   
|  6 | .fadnIn()    | 透明淡入顯示  | 
|  7 |  .fadeOut()  | 透明淡出消失  |   
|  8 | .fadeTo()    |  指定透明度 | 
|  9 | .animate()   |  CSS2動畫 |   
|  10 | .stop       | 中斷動畫  | 
|  11 | .delay()    |  延遲做動畫 |   
|   |   |   | 

stop();
|  stop( [clearQueue], [gottoEnd] ) |  能停止指定元素正在執行的動畫  | 
|---|---|
| clearQueue  |  設定為true 的話, 則該指定元素會馬上停止接下來的各種動畫; 設定false 不會有作用  |  
| gottoEnd  |   設定為true 的話, 則該指定元素目前正在進行的動畫會馬上結束; 設定false 不會有作用 |  


