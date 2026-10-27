# 方方 Fangfang

台語轉換器：漢字 ⇄ 皓羅 ⇄ 方音，也讀台羅、白話字；華語查台語、各地講法、收藏。
網站：<https://unoki99.github.io/fangfang/>

- `index.html`：整個網站（資料、字型都在檔案裡）
- `audio/`、`leku/`：教育部辭典的詞條、例句音檔（原始檔案，未經修改）

相關專案：方方詞卡 App、方方 Safari 查詞擴充功能。

## 腔口讀音

網站只顯示教育部辭典「語音差異」和「詞彙比較」裡**記載的**各地讀音。辭典沒有記載的詞，就算選了腔口，也顯示通行讀音。（方方詞卡 App 另外會推算更多詞的腔口讀音，並用藍色標示。）

發現讀音或內容有問題，歡迎到 [Issues](../../issues) 告訴我們，謝謝！

*Local readings on this site are only those stated in the MOE dictionary. Feedback is welcome via [Issues](../../issues).*

## 資料來源與授權

本站與教育部無關，不是官方網站。

- **詞條、讀音、釋義、詞性、文白讀、例句、近反義詞、異用字、腔口差異、各地講法、人名姓氏讀音、華語對照詞**：教育部《臺灣台語常用詞辭典》 — [sutian.moe.edu.tw](https://sutian.moe.edu.tw/)，授權：[創用CC 姓名標示-禁止改作 3.0 臺灣](https://creativecommons.org/licenses/by-nd/3.0/tw/)。釋義、例句原文照錄，僅擷取部分欄位顯示。讀音依規則由台羅轉成皓羅、方音、白話字顯示。華語對照詞擷取自辭典的釋義與例句華語翻譯。
- **音檔**（`audio/`、`leku/`）：教育部《臺灣台語常用詞辭典》詞條與例句音檔，授權同上，原始音檔未經修改。
- **音節編碼**：YuRen-tw（Yu-Ren Pan）《rime-taigi-tps》的拼音系統，經作者同意使用 — [github.com/YuRen-tw/rime-taigi-tps](https://github.com/YuRen-tw/rime-taigi-tps)
- **單字常用度參考**：Rime《八股文》（LGPL-3.0） — [github.com/rime/rime-essay](https://github.com/rime/rime-essay)
- **皓羅拼寫系統**：Unoki99
- **自補詞條**：標示「自補」的詞條及讀音為 Unoki99 自行補充，非教育部辭典內容。
- **皓羅字型**：DejaVu Sans 的子集 — [dejavu-fonts.github.io](https://dejavu-fonts.github.io/)，授權見 [`licenses/DejaVu-LICENSE.txt`](licenses/DejaVu-LICENSE.txt)
- **方音**：臺灣方音符號 — [zh.wikipedia.org/zh-tw/臺灣方音符號](https://zh.wikipedia.org/zh-tw/臺灣方音符號)

**程式碼**：MIT 授權，見 [`LICENSE`](LICENSE)。辭典資料、音檔、字型不在 MIT 授權範圍內，各自依照上面的授權。
