# 01 HTML 和 CSS 簡介

HTML 構成網站的結構和內容，而 CSS 樣式化內容。Webflow 在您設計時生成此代碼。

在為 Web 構建時，了解 HTML 和 CSS 之間的關係會很有幫助。在本課中：

1. 了解瀏覽器如何呈現代碼
2. 檢查網站代碼
3. 了解 HTML 和 CSS
4. 在 Webflow 為您生成乾淨代碼的同時進行設計

#### 了解瀏覽器如何呈現代碼

當您訪問一個網站時，您在屏幕上看到的內容是您的瀏覽器決定如何呈現該網站的底層代碼的結果。它使用代碼中的信息來顯示每個人在加載頁面時看到的內容。

&#x20;

![](https://i.imgur.com/kNvxH9y.png)

#### 檢查網站代碼

您可以在大多數瀏覽器上檢查和臨時編輯源代碼。 打開 [Chrome DevTools](https://developer.chrome.com/docs/devtools/) : 並操作

1. 右鍵單擊並從彈出菜單中選擇檢查，或按Control + Shift + I （在 Windows 上）或Command + Option + I （在 Mac 上）
2. 在檢查器中編輯代碼以臨時更改瀏覽器中的內容

測試代碼和渲染內容之間的關係會很有趣。由於您只是在瀏覽器中進行本地更改，因此您的更新將在您刷新頁面後立即消失。

![](https://i.imgur.com/hAcZxul.png)

&#x20;&#x20;

![](https://i.imgur.com/Gb8P1Am.png)

在 HTML 中，我們過去使用內聯樣式逐行設置所有內容的樣式。更改字體系列、顏色或大小等簡單的事情需要在 HTML 中逐項更新。逐個更新站點元素是非常多餘的，並且很難更新單個站點範圍的樣式，例如基本段落元素的字體系列或字體大小。

![](https://i.imgur.com/5CQAhzU.png)

#### CSS：樣式

CSS（級聯樣式表）採用所有以前內聯編寫的樣式信息——顏色、邊框、大小、定位、排版等等——並將其移動到帶有類的單獨樣式文檔中。  我們的 HTML 中的任何元素都可以被賦予一個類名，以採用與該類關聯的樣式。

![](https://i.imgur.com/lC9F4zu.png)

在 CSS 文件中對該類進行更改，它會影響使用該類的任何元素。

![](https://i.imgur.com/U3ymjdJ.png)

#### 問題：代碼越來越難

回到網絡的早期，我們只需要知道最基本的標籤和屬性。時間流逝，互聯網真正開始成長。設備發生了變化，我們與網絡交互的方式變得更加個性化。

隨著這一切的發生，有必要重新裝備。隨著我們作為設計師和開發人員可以構建的東西的可能性增加，我們必須在幕後管理的所有事情的複雜性也增加了。&#x20;

![](https://i.imgur.com/OedUw0K.png)

今天，要成為一名成功的 Web 開發人員，您必須掌握 HTML、CSS、JS、數據庫、Sass、JavaScript 庫、CSS 庫、特定於瀏覽器的怪癖、瀏覽器版本、響應式設計、GitHub、jQuery、Java、圖像壓縮、加載速度、優化、搜索引擎優化——這個列表不斷增長，很快 Web 開發就感覺不可能進入。

#### 在 Webflow 為您生成乾淨代碼的同時進行設計

HTML 和 CSS 是網頁設計的主要基礎，提供結構和样式。理解這些概念很有用，但我們已經到了不再需要手動編寫 HTML 和 CSS 代碼的地步——因為 Webflow。&#x20;

![](https://i.imgur.com/hmQSODr.png)

我們為 Webflow 提供的是一種在構建網站時更快、更高效的方式。通過在畫布上直觀地創建和操作內容，我們可以直接與我們的 HTML、CSS 和屏幕上的所有其他內容進行交互。使用 Webflow，您可以直接連接到您正在操作的媒體。

我們不是畫草圖和輸出原型，而是經歷痛苦的設計迭代到開發移交過程，而是輸出可用於生產的代碼。因此，即使是最瘋狂的設計理念，您也可以將它們變為現實——而無需編寫代碼。