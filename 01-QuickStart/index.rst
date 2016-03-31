Python CMS 快速起步
===================

本文將以 Plone 5 網站開發框架為主角，進行名詞解釋，並介紹 Python 專案開發工具的操作方式。

Plone 快速簡介
--------------

架站軟體的選項很多，為什麼要選擇 Plone 呢？最大的幾項優點包括：首先，它的管理流程很直覺，功能操控容易上手，其次，它擁有絕佳的升級相容及系統安全記錄，成熟又穩定，並且內建多國語言支援。Plone 以 Python 語言開發而成，它的支援社群相當廣大積極，根據評比資料，Plone 在同類軟體裡，多個評分項目都拿到中上的成績，算是開放源碼裡的通才工具。

安裝 Plone 很簡單，下載安裝檔案後，很快就在 Linux 或 MacOS 等環境完成架站。它的預設內容型別，像是頁面 (Page)、新聞 (News Item)、活動 (Event)、群集 (Collection)，能夠滿足常見的應用場合，內建工具包括搜尋引擎、多尺寸縮圖、TinyMCE 編輯器等，方便使用者管理內容。它還內建會員管理和工作流程的支援，彈指之間，你就取得企業級的內容管理系統，不過，想要全面發揮它的能力和彈性，就得熟悉更多設計架構和進階技巧。

開發環境與工具
--------------

Plone 為了照顧程式開發人員的需求，提供一套開發框架，搭配一系列的擴充工具和測試工具，可以新增或開發各式模組，為系統增加其他功能特色，包括可以自製表單的型別工具，提昇互動體驗的 AJAX Widget 工具。在佈景主題的套用上，它預設採用 Diazo 技術，視覺設計能夠與功能開發完全獨立分工，設計師和工程師彼此不會干擾。它也導入 Mockup 開發機制，讓 Node.js 社群的成果，能夠更輕鬆地整合進 Plone 系統。

Plone 是以 Python 和 Zope 為基礎，在 2015 年之際，里程碑 Plone 5 正式登場，原本在 Plone 4 時代進行實驗的模組，像是 Diazo、Dexterity、Mockup、mr.bob，在 Plone 5 都成為預設工具。可以這樣說，如果之前沒有用過 Plone，那麼 Plone 5 是一個清爽開闊的嶄新版本，你不必牽就於舊包袱，像是 Archetypes 或 Skin，並可以透過 Diazo、Mockup 機制接軌更多新技術，像是 LESS、Bootstrap，還有一系列 Node.js 社群的開發工具。

Plone 5 提供現代化的佈景主題，符合 HTML5 規範，編輯內容時，搭配 TinyMCE 最新版程式碼，並使用 Autocomplete Widget 之類的操作介面，

http://plone-training.readthedocs.org/en/plone5/plone5.html
http://mockup-training.readthedocs.org/en/latest/intro.html
http://datakurre.pandala.org/2015/09/generating-plone-theming-mockups-with.html
http://www.managertoday.com.tw/columns/view/51194
Diazo, Dexterity, Mockup, mr.bob

