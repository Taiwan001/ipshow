# "ipshow" 一款可以調取使用者IP地區的開源網站
## 本項目是由Chat GPT 3.5寫出來的
如果喜歡這個開源項目 歡迎STAR!

介紹:

簡介： 本報告將介紹一個基於 HTML、CSS 和 JavaScript 的功能，用於獲取使用者地理位置信息、顯示 IP 地址所在地區和國家，並提供特效以增強使用者界面的互動體驗。

功能：

獲取使用者地理位置： 頁面提供了一個按鈕，使用者點擊後可以獲取其地理位置的緯度和經度。通過使用瀏覽器的地理位置 API，在獲得使用者授權後可以獲取使用者的位置信息。

顯示地區和國家信息： 獲取使用者地理位置後，頁面會使用逆地理編碼將緯度和經度轉換為使用者所在地區和國家的信息。這些信息將在頁面上的信息框中顯示。

點擊特效： 為了增強使用者界面的互動體驗，按鈕被賦予了點擊特效。當使用者點擊按鈕時，按鈕會稍微放大，增加一些視覺反饋。

代碼示例： 以下是這個功能的代碼示例，代碼使用 HTML、CSS 和 JavaScript 編寫。

<script>
<!-- HTML -->
<!DOCTYPE html>
<html>
<head>
  <title>地區和國家顯示</title>
  <style>
    /* ... (樣式定義，包括按鈕點擊特效等) ... */
  </style>
</head>
<body>
  <header>
    <h1>地區和國家顯示</h1>
  </header>
  <div id="content">
    <button class="button-effect" onclick="getUserLocation()">獲取我的位置</button>
    <div class="info-box" id="locationInfo"></div>
    <div class="info-box" id="ipInfo"></div>
  </div>
  
  <script>
    let ipAddress = ''; // 存儲 IP 地址

    function getUserLocation() {
      // ... (獲取使用者位置信息，並顯示地區和國家信息) ...
    }

    function getLocationInfo(latitude, longitude) {
      // ... (逆地理編碼，顯示地區和國家信息) ...
    }

    function showIpLocationOnMap() {
      // ... (在地圖上顯示 IP 位置的功能) ...
    }
  </script>
</body>
</html>
</script>
結論： 通過以上功能，使用者可以輕鬆地獲取自己的地理位置信息，並了解到所在地區和國家的相關信息。界面上的特效增加了使用者與頁面的互動感，為使用者提供更優質的使用體驗。

