
call back
```javascript
$(function(){
  $('#').animate({left:900}, 500, name)
  
  function name(){
    // code
  }
})
```

|   |   指令  |   |
|---|---|---|
| 1  |  $('this').siblings().css({backgroundColor:"C00"}); |  他->兄弟們->變紅色  |
| 2  |  $('this').siblings().eq(1).css({backgroundColor:"C00"}); |他->兄弟們->指定第二個->變紅色 |
| 3  |  $('this').siblings().filter(":odd").css({backgroundColor:"C00"}); | |
| 4  |  $('this').prent().css({backgroundColor:"C00"}); | 他->爸爸->變紅色 |
| 5  |  $('this').prents().css({backgroundColor:"C00"}); | 他->爸爸Ｓ->變紅色|
| 6  |  $('this').prent().siblings().css({backgroundColor:"C00"});  |  |
| 7  |  $('this').prent().siblings().eq(0).css({backgroundColor:"C00"});  | |
| 8  |  $('this').prent().siblings().eq(0).find("li").css({backgroundColor:"C00"});  | find("li") 只能用標籤|
| 9  |  $('this').prent().siblings().eq(0).find("li").eq(2).css({backgroundColor:"C00"});  | |

|   |   |
|---|---|
| eq(數字) |  在目前被選取到的同一層(兄弟) 之中可以指定抓出其中一個物件 | 
|  filtet("篩選") |  在目前被選取到的同一層(兄弟) 之中可以指定抓出其中的 好幾個物件 | 
|  find(標籤) |  在目前被選取到的物件 可以抓出他的下一層(小孩) 之中的物件 | 



