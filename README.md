# hw2 電商前端應用
b04704068 曾英睿

1.透過bootstrap carosel實現輪播功能
https://getbootstrap.com/docs/4.0/components/carousel/

2.透過bootstrap navs中的tab讓使用者在頁面中切換選擇要產品查詢或新增產品功能
https://getbootstrap.com/docs/4.0/components/navs/

3.搶低價功能- 透過parseInt抓取商品展示頁面上價錢低於500元的商品，並將價錢文字加上新的class,將font-weight變大並用紅色突顯，讓使用者可以快速發現便宜的產品。
 var priceNum = parseInt(itemPrice[i].textContent.replace(/[^\d]/g, ''));
        if (priceNum <= 500) {
            itemPrice[i].classList.toggle('cheap');
        }
並透過jquery selector與.text()設置讓搶低價按鈕的文字在點擊後會顯示開啟和關閉的toggle效果
if($('#lowPrice').text() ＝＝ "開啟搶低價功能") {
        $('#lowPrice').text("關閉搶低價功能");else...
}

4.參考老師的程式碼實現商品展示與新增商品功能

5.透過bootstrao pagination 實現頁尾的分頁功能
https://getbootstrap.com/docs/4.0/components/pagination/

5.新增小米logo, 並將按鈕顏色,分頁和部分文字修改為品牌橘色

6.使用fontawesome替產品查詢與新增產品功能增加icon
