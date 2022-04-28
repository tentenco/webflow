# 04 元素 - Section

[https://www.youtube.com/watch?v=lMvfrbE2PJw\&t=3s](https://www.youtube.com/watch?v=lMvfrbE2PJw\&t=3s)

Section 是寬度為 100% 的佈局元素，延伸到瀏覽器窗口的整個寬度。部分在頁面的結構和佈局中起著重要作用。部分可讓您創建單獨的內容塊並將頁面劃分為有意義的部分。

![](https://i.imgur.com/cGyZrl3.png)

在本課中，你將學到：

1. 添加一個 Section
2. 為 Section 設置樣式
3. 最小高度
4. 視口高度
5. 添加 3D 透視圖

您可以從“元素”面板(A)中將 Section 元素添加到您的頁面。默認情況下，Section 將跨越主體的整個寬度。

同樣默認情況下，部分內部沒有填充。如果您不希望您的內容跨越正文的寬度，請拖入一個 Container 以使元素在頁面上居中。

#### 為 Section 設置樣式

Section 的高度會根據其內容自動調整——當您添加元素時，該部分會變得更高。您還可以在樣式面板中設置特定的高度。

#### 命名 Class

Weblfow 允許您添加不同的 class 名稱，並且基於原始 Section 分類 - 您可以覆蓋樣式並在組合類之上添加樣式。&#x20;

![](https://i.imgur.com/EfOfnHK.png)

#### 自動高度

當您將文本和媒體添加到 Section 時，高度會更改以定義高度。無論您添加多少內容，Section 高度都跟著裡面的內容。

一個 Section 的 padding 也會影響它的高度。最佳做法是設置 Section 的頂部和底部填充並添加內容以使其相應調整。&#x20;

![](https://i.imgur.com/aHBOhpL.png)

#### 使用 flexbox 使內容居中

使用 Section 中的容器，選擇 Section，並將其設置為flex。你就可以垂直置中它的子元素（垂直且置中於container）。&#x20;

![](https://i.imgur.com/EQocAnY.png)

#### 視角 Viewport height (vh)

例如，100vh將填充 100% 的視角高度。將其設置為 50vh將填充視口高度的 50%，依此類推。&#x20;

![](https://i.imgur.com/WAbTJSr.png)

#### 添加 3D 透視圖

如果您有一個部分的子項（一個部分內的任何元素，即使它們在一個部分內的其他元素內），您可能希望在 3D 空間中添加旋轉或移動。如果每個元素都應用了相同的類，那麼您將一次性設置所有元素的樣式。&#x20;

![](https://i.imgur.com/VThJ6ih.png)

然後添加一個 3D 變換，任何類型的 3D 移動看起來都有些平坦（這是因為它是等距投影，而我們可能想要的效果是透視投影。）

![](https://i.imgur.com/uPR5OGl.png)

要演示透視投影，請保持旋轉不變，並啟用 3D 相機效果。 選擇部分後，單擊變換設置並添加子透視圖（影響子元素的透視圖）。

較高的子視角值是一種更平坦的效果，就像使用長焦鏡頭將相機對準遠處的物體 - 而較低的值就像是使用廣角鏡頭更接近物體。&#x20;

![](https://i.imgur.com/yBFkSJo.png)

子透視將像 Section 這樣的元素轉換為類似相機的效果，為其任何子元素（層次結構中的任何子元素）啟用 3D。

這就是 Webflow Designer 中各部分的概述。
