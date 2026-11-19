# 東京住宿與日本機場鐵路選站

先決定住東京哪個站區，再反查機場進城方案。比較東京站的長途接駁、新宿的西側行程，以及品川與羽田的銜接。京都、大阪和博多供跨城市旅程使用。

## 資料與工具

| 分類 | 站點 | 方式 | 出發前核對 |
|---|---|---|---|
| NRT 成田 | 東京站 | Narita Express | 訂位前確認班次停站及飯店所在出口。 |
| NRT 成田 | 新宿 | Narita Express | 先比對班次終點，再核對飯店在車站東側或西側。 |
| HND 羽田 | 濱松町 | 東京單軌電車 | 前往其他地區時，另外核對轉乘站及站外步行。 |
| HND 羽田 | 品川 | 京急線 | 確認列車停品川，並查下一段新幹線或市區交通。 |
| KIX 關西 | 大阪站 | HARUKA | 訂房前區分大阪站與新大阪站。 |
| KIX 關西 | 京都站 | HARUKA | 若住河原町，京都站仍可能需要接駁。 |
| FUK 福岡國內線 | 博多 | 福岡市地下鐵 | 地下鐵接國內線航廈。 |
| FUK 福岡國際線 | 博多 | 航廈接駁巴士＋地下鐵 | 國際線可先接駁至國內線，再轉地下鐵。 |

[下載 CSV](travel-data.csv)。欄位包括交通分類、站點、方式、行前查核事項、來源與核對日期。需要票價、班次或無障礙動線時，請在出發前查相應營運方。

## 使用方式

執行 `python3 plan.py "NRT"`，或省略條件列出全部。工具使用 Python 3 標準函式庫。

[開啟獨立住宿區位資料集](hotel-areas/README.md)，可下載 CSV／JSON 及查看逐列來源。

## 住宿與相關交通攻略

- [東京住宿區域與酒店選擇](https://todolist-japan.com/zh/tokyo-hotel-accommodation/)
- [東京 JR 車站附近住宿](https://todolist-japan.com/zh/tokyo-jr-station-hotels/)
- [成田機場到東京站](https://todolist-japan.com/zh/narita-airport-to-tokyo-station/)
- [成田機場到新宿交通](https://todolist-japan.com/zh/narita-airport-to-shinjuku/)
- [關西機場到大阪交通](https://todolist-japan.com/zh/kansai-airport-to-osaka-transport/)
- [關西機場到京都的交通攻略](https://todolist-japan.com/zh/kansai-airport-to-kyoto-transport/)
- [福岡機場到博多的交通選項](https://todolist-japan.com/zh/fukuoka-airport-to-hakata-transport-guide/)

## 資料來源

- [來源 1](https://www.narita-airport.jp/en/access/train/?vm=r)
- [來源 2](https://www.tokyo-haneda.com/en/access/train/index.html?tab=terminal2)
- [來源 3](https://www.westjr.co.jp/travel-information/en/tickets-passes/oneway/haruka/)
- [來源 4](https://www.fukuoka-airport.jp/en/access/subway.html)

最近核對日期 2026-11-19。

## 官方網站

[Todolist Japan 官方網站](https://todolist-japan.com/zh/homepage/)

## 授權與貢獻

[授權](LICENSE.md)涵蓋專案原創程式與文字。第三方來源維持各自的權利聲明。提交修正時請附官方資料 URL、查核日期及受影響的 CSV 列。可執行 `python3 check.py --offline` 先驗證資料結構。
