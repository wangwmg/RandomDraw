# 隨機抽籤系統

[English](README.md) | [简体中文](README_zh-CN.md) | 繁體中文

## 概述

隨機抽籤系統是一個簡單且高效的網頁應用程式，專為根據輸入數據進行隨機抽籤而設計。不論是抽獎、隊伍分配，或是任何需要隨機結果的活動，此工具都能提供一個安全且直觀的體驗。所有運算過程皆在您的瀏覽器中本地執行，確保資料的隱私性。

## 功能特點

- **本地運算：** 所有的隨機抽籤都在您的瀏覽器中進行，您的資料不會離開您的裝置。
- **可自訂的輸入：** 輸入格式化的數據，包括名字和對應的抽籤次數，以符合您的特定需求。
- **彈性的抽籤選項：** 設定要生成的結果數量，以及抽籤範圍的最大`times`值。
- **使用者友好的介面：** 系統具有簡潔且響應迅速的介面，可在現代瀏覽器中流暢運行。
- **結果追蹤：** 系統會記錄抽籤的時間，並且追蹤從頁面開啟以來按下抽籤按鈕的次數。

## 使用方法

1. **輸入數據：** 將格式化的數據貼到文字框中。格式應為 `name times`（例如，`小明 3`），其中 `name` 是參加者的名字，`times` 代表該參加者在這次抽籤前參加活動的次數。
2. **設定抽籤參數：**
   - 輸入要產生的結果數量。
   - 設定最大的 `times` 值，也就是參加者的 `times` 如果小於或等於這個值，則會有機會被抽中（不論 `times` 是多少，所有參加者的中籤機率都是相同的）。
3. **產生結果：** 點擊「生成隨機結果」按鈕，系統會根據輸入的數據和設定進行抽籤。
4. **查看結果：** 結果將顯示在按鈕下方，並顯示被選中的參加者、他們的原始`times`值、抽籤使用的隨機種子，以及抽籤發生的精確時間。

## 授權條款

本程式依據 GNU 通用公共授權條款 v3.0 授權發佈。您可以在 [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html) 查閱該授權條款的副本。

- 您可以在相同的授權條款下使用、修改與分發本軟體。
- 任何修改都必須依相同條款進行分享。
- 除 GPL 規定之外，不得對本軟體施加額外的限制。

## 參與貢獻

歡迎您為此專案貢獻！如果您有改善建議、錯誤修正或新功能的點子，歡迎 fork 此程式庫並提交 pull request。所有有助於系統改進的貢獻我們都非常感謝。

## 作者

此系統由 [wangwmg](https://github.com/wangwmg) 開發。如果您有任何問題或建議，請在 [GitHub 專案庫](https://github.com/wangwmg/RandomDraw) 提交 issue。

---

**Disclaimer:** This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
