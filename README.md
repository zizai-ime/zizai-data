# 字在資料更新檔

[字在（ZiZai）](https://github.com/zizai-ime/zizai-ime)是為正體中文（繁體）設計的中文輸入法。這裡發布它的資料更新檔（ `.zizaipack` ）：更新過的字根表與字頻表，套用後不必重新安裝字在。

目前還沒有發布資料更新檔。

## 怎麼更新

需要字在 1.1.0 以上的電腦版（macOS、Windows、Linux）。

- **在字在裡更新**：在「字在設定」的首頁按「檢查更新」；有新的資料更新檔時，按「下載並看改了哪些字」，看過再按「套用」。
- **自己下載**：從 [Releases](https://github.com/zizai-ime/zizai-data/releases) 下載 `.zizaipack` ，在首頁按「匯入資料更新檔…」，或在 Finder、檔案總管裡按兩下這個檔。

資料更新檔只換掉內建的字根表與字頻表，詞庫、擴充字根表與設定都不受影響；隨時可以在首頁按「改回內建資料」。

## 每個 Release 有什麼

Release 的標籤就是資料版本，例如 `2026-11-01.1` 。

| 檔案 | 說明 |
|---|---|
| `zizai-data-<資料版本>.zizaipack` | 資料更新檔 |
| `zizai-data-stable.zizaipack` | 同一個資料更新檔，檔名固定，字在用它下載最新版 |
| `.sha256` | 上面兩個檔案各自的 SHA-256 |

Release 說明會列出這一版改了輸入碼的字（只列字，不列碼）。

## 使用條款與資料來源

資料更新檔裡的資料只供在字在裡使用，適用字在的[使用條款](https://github.com/zizai-ime/zizai-ime/blob/main/LICENSE.md)（第 4 條「資料更新檔」）。未經字在開發小組同意，不得販售更新檔或檔案裡的資料，不得把它重新包裝、修改後散布，不得把它附在其他產品裡散布，也不得把它放到其他網站或服務供人下載；請分享這一頁的連結。

每個資料更新檔裡附 `NOTICE.md` ，列出第三方資料的來源與授權：

- 拆字資料：數位發展部，「[CNS11643 中文標準交換碼全字庫](https://www.cns11643.gov.tw)」。此開放資料依政府資料開放授權條款 (Open Government Data License) 進行公眾釋出，使用者於遵守本條款各項規定之前提下，得利用之。政府資料開放授權條款： https://data.gov.tw/license
- 字頻：國家教育研究院〈民國112年語料字頻表〉（《解讀媒體字詞：新聞與社群媒體用語調查（112年）》附錄 1），只使用「字」與「字頻」兩欄。國家教育研究院未參與本產品，亦不代表其建議、認可或贊同。

字在怎麼處理你的資料，見[隱私權政策](https://github.com/zizai-ime/zizai-ime/blob/main/PRIVACY.md)。

## 問題與建議

請到字在的 [Issues](https://github.com/zizai-ime/zizai-ime/issues) 回報。Issues 是公開的，請不要貼上字根表內容、詞庫或打字內容。

© 2026 字在開發小組
