# Japan Hotel Location & Accessibility Dataset｜東京與大阪住宿站區

機場入境和隔日列車是兩個獨立選擇。先找有想搭的路線的站區，再核對酒店地址與站外出口。

## 用法

在下面比較交通方式與出發前查核事項。也可下載 [CSV](data.csv) 或 [JSON](data.json)，依城市或下一程用途篩選。考慮輪椅、嬰兒車或大型行李時，先以營運方的電梯及無障礙路徑公告確認完整動線。

NRT 東京站／新宿俱有 N’EX 服務。以 HARUKA 為起點則可比較大阪站與新大阪站。

| 城市 | 站區 | 可核實銜接 | 適合先比較的情境 | 訂房前核對 | 來源 |
|---|---|---|---|---|---|
| 東京 | 東京站 | 成田 N’EX | 隔日長途鐵路 | 確認 JR 入口與住宿是丸之內或八重洲側。 | [來源](https://www.narita-airport.jp/en/access/train/?vm=r) |
| 東京 | 新宿 | 成田 N’EX | 東京西側行程 | 確認列車確實停新宿，並按酒店地址選出入口。 | [來源](https://www.narita-airport.jp/en/access/train/?vm=r) |
| 東京 | 品川 | 羽田京急線 | 鐵路轉乘 | 依航廈及當日列車停站核對，帶行李時另查月台動線。 | [來源](https://www.tokyo-haneda.com/en/access/train/index.html?tab=terminal2) |
| 大阪 | 大阪站／梅田 | 關西機場 HARUKA | 大阪市區基地 | 確認酒店靠大阪站還是其他梅田站出口。 | [來源](https://www.westjr.co.jp/travel-information/en/tickets-passes/oneway/haruka/) |
| 大阪 | 新大阪站 | 關西機場 HARUKA | 隔日新幹線 | 機票、車票與飯店地址分別核對新大阪及大阪的站名。 | [來源](https://www.westjr.co.jp/travel-information/en/tickets-passes/oneway/haruka/) |
| 大阪 | 天王寺 | 關西機場 HARUKA | 大阪南側基地 | 核對酒店是否靠 JR 或地鐵入口，確認步行路線。 | [來源](https://www.westjr.co.jp/travel-information/en/tickets-passes/oneway/haruka/) |
| 大阪 | 難波站區 | 關西機場南海電鐵 Rapi:t | 大阪南區與機場往返 | 確認車票所寫南海難波站與酒店靠近的地鐵出口，按日期再查開行。 | [來源](https://www.nankai.co.jp/en_railway/traffic/express/rapit.html) |

## 資料字典

- `city`、`area_or_station` 為城市及比較單位，兩欄合併辨識一筆。
- `verified_connection` 為來源可核實的運輸連接或規劃參照。
- `planning_use_case` 及 `check_before_booking` 為 Todolist 編輯整理的選區情境與核對事項。
- `source_url` 與 `checked_on` 為該列的第一手來源及核對日期。

## 方法、限制與授權

逐列查營運機構或政府原始資料，整理基本站名及服務事實，另加原創的住宿選區判斷。涵蓋選定站區。班表、營運異動、無障礙狀態、酒店距離、價格與評價請向各營運方及酒店核對。原創文字及欄位設計依 [專案授權](../LICENSE.md) 提供，原始資料頁、地圖和商標各依權利人條款。

資料核對日期 2026-11-19。

## 延伸住宿攻略

- [東京住宿分區](https://todolist-japan.com/zh/tokyo-hotel-accommodation/)
- [大阪住宿分區](https://todolist-japan.com/zh/osaka-hotel-accommodation/)
