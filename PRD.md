一、PRD（Product Requirement Document）
1️⃣ 目標

建立一個最基本的 Blazor Server 專案，可顯示首頁和簡單頁面，供後續擴展功能與測試 CI/CD workflow。

2️⃣ 功能需求

首頁 / 顯示歡迎訊息。

頁面 /counter 可以點擊按鈕增加計數。

頁面 /fetchdata 顯示靜態資料表（假設 API 測試）。

可以使用 Razor Components 進行簡單 UI 渲染。

3️⃣ 技術需求

.NET 8 / Blazor Server

HTML、CSS、Razor

可用 GitHub Actions workflow build 測試專案

4️⃣ 測試需求

dotnet build 可以成功。

/counter 按鈕點擊會增加計數（可在 workflow 使用 dotnet run 搭配簡單 curl 測試）。

頁面 /fetchdata 正確渲染表格內容。
