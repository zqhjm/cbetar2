# CBETA電子佛典閱讀器2(非官方)

## 特色

搜尋經文、書籤功能、離線瀏覽、暗色模式、字型調整、直式文字、app更新。

## 介紹

CBETA電子佛典閱讀器2(非官方)，使用CBETA API存取電子佛經，支援以下功能

* 搜尋
    1. 在目錄頁，按下右上角放大鏡圖示。在對話框輸入經文部分標題，確認後會列出相關經文。
    ![Search](https://github.com/MrMYHuang/cbetar2/raw/master/docs/images/Search.png)
* 書籤
    1. 開啟某經文後，長按後選擇想標記為書籤的字串位置，再按右上角書籤圖示，會變紅色，即新增一書籤，可至書籤頁查詢。
    2. 在書籤頁點擊某一書籤，即會開啟經文，並自動跳至標記文字的位置。
    3. 若要同一經文新增多個書籤，操作方法為:新增一個書籤後，按左上角上一頁箭頭，再重點同一經文，書籤會變回白色，即可新增下一個書籤。
* 離線瀏覽
    1. 書籤頁包含的經文都具有離線瀏覽的功能。
* 字型調整
    1. 考量視力不佳的同修，提供最大64px的經文字型設定。若有需要更大字型，請E-mail或GitHub聯絡開發者新增。
    2. 支援全字庫楷書字型。
* 直式文字
    1. 傳統中文書的直式文字、由右至左排版。
* App更新

    此app不定期發佈更新，包含新功能或bug修正。注意!App檔案更新後，要關閉、重啟1次app才會載入新版程式。目前支援2種更新方式:

    1. App啟動: app啟動後，會自動檢查一次有無新版。
    2. 手動: 至設定頁，按更新按鈕。

程式碼為開放，可自由下載修改。

## 程式

使用Ionic開發的Web App (PWA)，請參考 https://ionicframework.com/ 作開發環境建置。已在這些環境作過安裝、測試:

* Windows 10 + Edge Chrome
* Android 9 + Chrome
* macOS 10.15 + Edge Chrome
* iPad 7 (模擬器) + Safari
* iPhone 8 (模擬器) + Safari
* Debian Linux 10 + Chrome

## Run Locally
git clone https://github.com/MrMYHuang/cbetar2.git
cd cbetar2
npm run start

## Web App網址
https://MrMYHuang.github.io

## 版本歷史
* 1.6.0:
    * 支援經文捲軸。
* 1.5.10:
    * 使用全字庫字型作楷書支援。
* 1.5.1:
    * 支援直式文字與楷書。
* 1.2.26:
    * 修正app無法在Chrome安裝的問題。
* 1.2.20:
    * 支援app啟動與手動檢查更新。
* 1.0.0:
    * 第1版。

## 隱私政策聲明

此app無收集使用者個人資訊。

## 第三方軟體版權聲明

1. 全字庫字型

    此app使用的全字庫字型(2020-08-18版)由國家發展委員會提供。此開放資料依政府資料開放授權條款 (Open Government Data License) 進行公眾釋出，使用者於遵守本條款各項規定之前提下，得利用之。政府資料開放授權條款：https://data.gov.tw/license