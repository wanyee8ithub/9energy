九大能量中心 離線版

檔案
  index.html            整個 app
  manifest.webmanifest  讓手機可以「安裝」成 app
  sw.js                 離線快取
  icons/                圖示

放到 GitHub Pages
  1. 建一個新的 repository（不要放進 yourdesign 人類圖的 repository，會蓋掉它）。
  2. 把這個資料夾裡的所有檔案，連同 icons 資料夾，一起上傳。
  3. Settings > Pages，Branch 選 main，資料夾選 /(root)，儲存。
  4. 等一兩分鐘，用 Pages 給你的網址在手機上打開。第一次要有網路。

安裝到手機
  Android Chrome：右上角選單 > 安裝應用程式（或加到主畫面）。
  iPhone Safari：分享按鈕 > 加入主畫面。
  裝好後開飛航模式也能用。

更新
  修改 index.html 重新上傳後，有網路時重開 app 一到兩次就會換成新版。
  如果一直沒換，把 sw.js 第一行 "hd9-v1" 改成 "hd9-v2"（之後依序加一）再上傳。

筆記
  筆記存在這部手機的瀏覽器裡，不會同步到別的裝置。
  iPhone 上，加到主畫面的 app 和 Safari 的筆記是分開的。
  清除瀏覽器資料會一併清掉筆記。
