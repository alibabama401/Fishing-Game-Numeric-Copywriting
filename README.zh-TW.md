# 捕魚數值文案與玩法設定

[简体中文](README.zh-CN.md) · **繁體中文** · [English](README.en.md) · [圖文產品頁](https://alibabama401.github.io/Fishing-Game-Numeric-Copywriting/zh-tw/)

面向捕魚數值文案、玩法設定與遊戲策劃搜尋需求，整理模式結構、數值變數、Unity Lua 入口、Proto3 協定檔案和真實除錯截圖。

**捕魚數值文案 · 捕魚玩法設定 · 捕魚遊戲策劃 · 遊戲平衡 · Unity Lua · Protobuf · 街機捕魚**

![捕魚遊戲大廳與模式選擇](docs/assets/screenshots/lobby.png)

## 專案概覽

- GitHub: https://github.com/alibabama401/Fishing-Game-Numeric-Copywriting
- Pages: https://alibabama401.github.io/Fishing-Game-Numeric-Copywriting/
- 展示捕魚遊戲數值文案、經典與比賽模式、玉石場和海魔活動，並結合 Unity Lua、Proto3 協定、設定變數、除錯場景及 12 張真實產品截圖。

## 功能與玩法

| Area | Evidence-based description |
| --- | --- |
| 核心數值變數 | 魚的血量與分值、刷新頻率、砲台傷害、暴擊概率、子彈速度。 |
| 模式與活動設定 | 經典模式、比賽模式、玉石場、海魔來襲、鍛造與休閒小遊戲。 |
| 回饋與除錯 | 戰鬥截圖展示獎勵回饋、砲倍解鎖、任務目標及除錯數值覆蓋層。 |
| 設定與協定 | Lua 入口、Unity 輔助模組、AssetBundle 相關引用和多組 Proto3 訊息定義。 |

## 技術證據

| Evidence | What it shows |
| --- | --- |
| Unity 與 Lua 證據 | `Main.lua` 引用了 Unity 輔助模組、CS2Lua、AssetBundle、本地化、音訊與網路服務。 |
| 協定層 | 公開 `.proto.bytes` 檔案使用 Proto3，涵蓋登入、大廳、活動、聊天、俱樂部、郵件、記錄與設定訊息。 |
| 數值設計變數 | 倉庫說明涉及魚的血量/分值、刷新頻率、砲台傷害、暴擊概率和子彈速度。 |
| 證據邊界 | 截圖可證明玩法模式與除錯涵蓋；沒有可重現資料時，不宣稱流水、留存或付費提升。 |

## 產品截圖

![捕魚遊戲大廳與模式選擇](docs/assets/screenshots/lobby.png)

*捕魚遊戲大廳與模式選擇*

![經典捕魚模式](docs/assets/screenshots/classic-mode.png)

*經典捕魚模式*

![捕魚比賽模式](docs/assets/screenshots/tournament-mode.png)

*捕魚比賽模式*

![海魔來襲活動玩法](docs/assets/screenshots/haimo.png)

*海魔來襲活動玩法*

![玉石場玩法](docs/assets/screenshots/jade-arena.jpg)

*玉石場玩法*

![玉石場大廳](docs/assets/screenshots/yushidating.png)

*玉石場大廳*

![經典捕魚戰鬥](docs/assets/screenshots/jingdian.png)

*經典捕魚戰鬥*

![砲台鍛造系統](docs/assets/screenshots/duanzhao.jpg)

*砲台鍛造系統*

![休閒捕魚小遊戲介面一](docs/assets/screenshots/xiaoyouxi1.png)

*休閒捕魚小遊戲介面一*

![休閒捕魚小遊戲介面二](docs/assets/screenshots/xiaoyouxi2.png)

*休閒捕魚小遊戲介面二*

![戰鬥除錯與數值回饋](docs/assets/screenshots/zhandou2.jpg)

*戰鬥除錯與數值回饋*

![戰鬥場景與獎勵回饋](docs/assets/screenshots/zhandou3.jpg)

*戰鬥場景與獎勵回饋*


## 联系与使用说明

- Email: [ttpoker40@gmail.com](mailto:ttpoker40@gmail.com)
- Telegram: [@alibabama401](https://t.me/alibabama401)

## 倉庫範圍

本 README 僅描述公開倉庫中可見的證據。整合前請核對建置依賴、完整度、授權、安全性與素材權屬。搜尋可見度可以改善，但不能保證固定排名。
