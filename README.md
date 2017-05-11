# MindfulTimer

這是一個結合了正念（Mindful）概念的簡單計時器。

## 使用方式
因為我們在工作的過程中，很容易分心去做別的事情，因此在開始計時前，需要先設定工作任務，時間一到計時器會跳出視窗，你需要在這時候檢視自己是否於該時段內進行該任務，還是其實你已經分心到其他事物或其他工作項目上。

最重要的是在時間到時，**檢視自己有沒有在設定的工作項目上**。

## 特色

內建筆記本功能，讓你不用另外開記事本來儲存需要暫存的資料，會自動將記事內容儲存於本機端（清除瀏覽記錄將一併清除）。

## 提醒方式

提醒的方式是使用瀏覽器原生的方式，雖然畫面沒那麼好看，但是比起嗶嗶聲或其他的彈跳視窗，這是最有效打斷並提醒你的方式。

另外，不使用音效是因為在工作時，大部分的人並不會開聲音（除非你帶耳機），因為開聲音可能會干擾到其他同事。

## 給開發者

由於本人美感欠佳，不太會設計畫面，因此非常歡迎對介面設計有興趣的開發者，可以 FORK 本專案，並透過 Pull Request 的方式，一起提升這個方案。

#### 開發方式

下載本專案後，於 Terminal 上進入本專案資料夾，先執行 `npm install`，接著執行 `gulp` ，這會幫你自動建立本地端的測試環境，並且編譯 SCSS 檔案。

#### 修改 CSS
CSS 的檔案放在 `./src/sass` 這個資料夾中，之後會透過 SCSS 編譯，因此如果你不熟悉 SCSS 的其他功能，你也可以直接用 CSS 修改。

#### 修改 JS
JS 的檔案放在 `./src/js` 這個資料夾中，可自行修改。

#### 第三方套件
第三方的套件都會放在 `./vender/` 這個資料夾中。目前有使用到 Bootstrap, sweetalert2(掛載但未用), jQuery, lodash 這幾個套件。
