<div align="center">

<img alt="LOGO" src="https://cdn.jsdelivr.net/gh/MaaAssistantArknights/design@main/logo/maa-logo_512x512.png" width="256" height="256" />

# MaaAssistantArknights

*MAA 的文檔以簡體中文為主，其他語言的文檔可能品質低或尚未翻譯，請諒解。*

<br>
<div>
    <img alt="C++" src="https://img.shields.io/badge/C++-20-%2300599C?logo=cplusplus">
</div>
<div>
    <img alt="platform" src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-blueviolet">
</div>
<div>
    <img alt="license" src="https://img.shields.io/github/license/MaaAssistantArknights/MaaAssistantArknights">&#20;
    <img alt="commit" src="https://img.shields.io/github/commit-activity/m/MaaAssistantArknights/MaaAssistantArknights?color=%23ff69b4">
</div>
<div>
    <img alt="stars" src="https://img.shields.io/github/stars/MaaAssistantArknights/MaaAssistantArknights?style=social">&#20;
    <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/MaaAssistantArknights/MaaAssistantArknights/total?style=social">
</div>
<br>

[简体中文](../zh-cn/readme.md) | 繁體中文 | [English](../en-us/readme.md) | [日本語](../ja-jp/readme.md) | [한국어](../ko-kr/readme.md)

MAA 的意思是 MAA Assistant Arknights

一款明日方舟遊戲小助手

基於圖像辨識技術，一鍵完成全部日常任務！

絕讚更新中  ✿✿ヽ(°▽°)ノ✿<br>

</div>

## 亮點功能

- 刷新理智，掉落物品辨識及上傳至 [企鵝物流](https://penguin-stats.cn/)，[一圖流](https://ark.yituliu.cn/)。
- 智能基建換班，自動計算幹員效率，單一設施內最優解；同時也支援 [自訂排班](./protocol/base-scheduling-schema.md)。
- 自動公開招募，可選擇使用加急許可，一次全部刷完！公開招募數據自動上傳至 [企鵝物流](https://penguin-stats.cn/result/stage/recruit/recruit)，[一圖流](https://ark.yituliu.cn/survey/maarecruitdata)。
- 支援手動辨識公開招募界面，方便對高星公開招募做出選擇 ~~（你的這個高姿回費出的是推王呢還是推王呢）~~。
- 支援辨識幹員列表，統計已有和未有幹員及潛能，並在公開招募辨識顯示。
- 支援辨識養成材料，並導出至 [企鵝物流刷圖規劃](https://penguin-stats.cn/planner)、[明日方舟工具箱](https://arkntools.app/#/material)、[ARK-NIGHTS 幹員培養表](https://ark-nights.com/settings)。
- 造訪好友、收取信用及購物、領取日常獎勵等，一鍵全日常自動長草。
- 肉鴿全自動刷源石錠和等級，自動燒水和凹直升，智能辨識幹員及練度。
- 選擇作業 JSON 文件，自動抄作業，[視頻演示](https://www.bilibili.com/video/BV1H841177Fk/)。
- 支援 C, Python, Java, Rust, Golang, Java HTTP, Rust HTTP 等多種接口，方便集成調用，自訂你的 MAA！

話不多說，看圖！

![zh1](https://user-images.githubusercontent.com/9762652/259595058-1529207a-ef3d-4eca-a016-4759eb534c6e.png)
![zh2](https://user-images.githubusercontent.com/9762652/259594965-882b61e6-bf31-40c1-8c03-3f51f82a0d42.png)
![zh3](https://user-images.githubusercontent.com/9762652/259594874-07abdd9f-33f0-4446-8da3-799849bf7328.png)
![zh4](https://user-images.githubusercontent.com/9762652/259594649-c08b6558-7d17-45a8-9ba0-3ebc9a6f5589.png)

## 下載地址

前往[官網](https://maa.plus)自動匹配鏡像源並下載穩定版，或：

- [穩定版/公測版](https://github.com/MaaAssistantArknights/MaaAssistantArknights/releases)
- [內測版](https://github.com/MaaAssistantArknights/MaaRelease/releases)

## 使用說明

### 基本說明

請參閱 [新手上路](./manual/newbie.md) 與 [功能介紹](./manual/introduction/)。

### 常見問題

- 軟體一打開就閃退；
- 連接錯誤、不知道 ADB 路徑怎麼填寫；
- 連接成功了，但沒反應；
- 如何連接自定義端口；
- 下載速度慢，且鏡像站無法打開網頁；
- 下載到一半提示“登錄”/“鑑權”；
- 連接正常，任務開始了，但是沒反應。

請參閱 [常見問題](./manual/faq.md)。

### 外服支援

目前國際服（美服）、日服、韓服、繁中服的絕大部分功能均已支援。但由於外服使用者較少及項目人手不足，很多功能並沒有進行全面的測試，所以請自行體驗。  
若您遇到了 Bug，或對某個功能有強需求，歡迎在 [Issues](https://github.com/MaaAssistantArknights/MaaAssistantArknights/issues) 和 [討論區](https://github.com/MaaAssistantArknights/MaaAssistantArknights/discussions) 催更；或加入我們一起建設 MAA！請參閱 [外服適配教程](#外服適配)

### CLI 支援

MAA 支援命令列介面（CLI）操作，支援 Linux、macOS 和 Windows，可用於自動化腳本或在無圖形介面的伺服器上使用。請參閱 [CLI 使用指南](./manual/cli/intro.md)

## 加入我們

### 主要相關專案

**目前專案組非常缺前端大佬，若您有相關經驗，歡迎加入我們！**

- 全新框架：[MaaFramework](https://github.com/MaaXYZ/MaaFramework)
- 全新 GUI：[MaaX](https://github.com/MaaAssistantArknights/MaaX)
- [作業站](https://prts.plus) 前端：[maa-copilot-frontend](https://github.com/MaaAssistantArknights/maa-copilot-frontend)
- [作業站](https://prts.plus) 後端：[MaaBackendCenter](https://github.com/MaaAssistantArknights/MaaBackendCenter)
- [官網](https://maa.plus)：[前端](https://github.com/MaaAssistantArknights/maa-website)
- 深度學習：[MaaAI](https://github.com/MaaAssistantArknights/MaaAI)

### 多語言 (i18n)

MAA 支援多國語言，並使用 Weblate 進行本地化管理。如果您精通多種語言，歡迎前往 [MAA Weblate](https://weblate.maa-org.net) 幫助我們進行翻譯。

MAA 以中文（簡體）為第一語言，翻譯詞條均以中文（簡體）為準。

[![Weblate](https://weblate.maa-org.net/widgets/maa-assistant-arknights/zh_Hans/maa-wpf-gui/multi-auto.svg)](https://weblate.maa-org.net/engage/maa-assistant-arknights/zh_Hans/)

### 參與開發

#### Windows

請參閱 [開始開發](./develop/development.md)。

#### Linux | macOS

請參閱 [Linux 編譯教程](./develop/linux-tutorial.md)。

#### API

- [C 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/include/AsstCaller.h)：[集成示例](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Cpp/main.cpp)
- [Python 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Python/asst/asst.py)：[集成示例](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Python/sample.py)
- [Golang 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/tree/dev/src/Golang)：[集成示例](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Golang/maa/maa.go)
- [Dart 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/tree/dev/src/Dart)
- [Java 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Java/src/main/java/com/iguigui/maaj/easySample/MaaCore.java)：[集成示例](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Java/src/main/java/com/iguigui/maaj/easySample/MaaJavaSample.java)
- [Java HTTP 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Java/Readme.md)
- [Rust 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/tree/dev/src/Rust/src/maa_sys)：[HTTP 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/tree/dev/src/Rust)
- [TypeScript 接口](https://github.com/MaaAssistantArknights/MaaX/tree/main/packages/main/coreLoader)
- [Woolang 接口](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Woolang/maa.wo)：[集成示例](https://github.com/MaaAssistantArknights/MaaAssistantArknights/blob/dev/src/Woolang/demo.wo)
- [集成文檔](./protocol/integration.md)
- [回呼消息協議](./protocol/callback-schema.md)
- [任務流程協議](./protocol/task-schema.md)
- [自動抄作業協議](./protocol/copilot-schema.md)

#### 外服適配

請參閱 [外服適配教程](./develop/overseas-client-adaptation.md)，對於國服已支援的功能，絕大部分的外服適配工作僅需要截圖 + 簡單的 JSON 修改即可。

#### 想參與開發，但不太會用 GitHub?

[GitHub Pull Request 流程簡述](./develop/development.md#github-pull-request-流程簡述)

#### Issue bot

請參閱 [Issue Bot 使用方法](./develop/issue-bot-usage.md)

## 致謝

### 開源庫

- 圖像辨識庫：[opencv](https://github.com/opencv/opencv.git)
- ~~文字辨識庫：[chineseocr_lite](https://github.com/DayBreak-u/chineseocr_lite.git)~~
- 文字辨識庫：[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- 深度學習部署庫：[FastDeploy](https://github.com/PaddlePaddle/FastDeploy)
- 機器學習加速器：[onnxruntime](https://github.com/microsoft/onnxruntime)
- ~~關卡掉落辨識：[企鵝物流辨識](https://github.com/penguin-statistics/recognizer)~~
- 地圖格子辨識：[Arknights-Tile-Pos](https://github.com/yuanyan3060/Arknights-Tile-Pos)
- C++ JSON 庫：[meojson](https://github.com/MistEO/meojson.git)
- C++ 運算符解析器：[calculator](https://github.com/kimwalisch/calculator)
- ~~C++ base64 編解碼：[cpp-base64](https://github.com/ReneNyffenegger/cpp-base64)~~
- C++ 解壓壓縮庫：[zlib](https://github.com/madler/zlib)
- C++ Gzip 封裝：[gzip-hpp](https://github.com/mapbox/gzip-hpp)
- 安卓觸控事件器：[minitouch](https://github.com/DeviceFarmer/minitouch)
- 安卓觸控事件器：[MaaTouch](https://github.com/MaaAssistantArknights/MaaTouch)
- WPF MVVM 框架：[Stylet](https://github.com/canton7/Stylet)
- WPF 控件庫：[HandyControl](https://github.com/HandyOrg/HandyControl) -> [HandyControls](https://github.com/ghost1372/HandyControls)
- C# 日誌：[Serilog](https://github.com/serilog/serilog)
- C# JSON 庫：[Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) & [System.Text.Json](https://github.com/dotnet/runtime)
- ~~下載器：[aria2](https://github.com/aria2/aria2)~~

### 數據來源

- ~~公開招募數據：[明日方舟工具箱](https://www.bigfun.cn/tools/aktools/hr)~~
- ~~幹員及基建數據：[PRTS Wiki](http://prts.wiki/)~~
- 關卡數據：[企鵝物流數據統計](https://penguin-stats.cn/)
- 遊戲數據及資源：[明日方舟客戶端素材](https://github.com/yuanyan3060/ArknightsGameResource)
- ~~遊戲數據：[《明日方舟》遊戲數據](https://github.com/Kengxxiao/ArknightsGameData)~~

### 貢獻/參與者

感謝所有參與到開發/測試中的朋友們，是大家的幫助讓 MAA 越來越好！ (\*´▽｀)ノノ

[![Contributors](https://contributors-img.web.app/image?repo=MaaAssistantArknights/MaaAssistantArknights&max=114514&columns=15)](https://github.com/MaaAssistantArknights/MaaAssistantArknights/graphs/contributors)

## 聲明

- 本軟體使用 [GNU Affero General Public License v3.0 only](https://spdx.org/licenses/AGPL-3.0-only.html) 開源。
- 本軟體 logo 並非使用 AGPL 3.0 協議開源，[耗毛](https://weibo.com/u/3251357314)、vie 兩位畫師及軟體全體開發者保留所有權利。不得以 AGPL 3.0 協議已授權為由在未經授權的情況下使用本軟體 logo，不得在未經授權的情況下將本軟體 logo 用於任何用途。
- 本軟體開源、免費，僅供學習交流使用。若您遇到商家使用本軟體進行代練並收費，可能由於設備或時間等原因，產生的任何問題及後果與本軟體無關。

## 廣告

使用者交流 QQ 群：[MAA 使用 & 粥游交流 QQ 群](https://ota.maa.plus/MaaAssistantArknights/api/qqgroup/index.html)  
使用者交流 TG 群：[Telegram 群](https://t.me/+Mgc2Zngr-hs3ZjU1)  
自動戰鬥 JSON 作業分享：[prts.plus](https://prts.plus) 或 [抄作业.com](http://抄作业.com)  
Bilibili 直播間：[直播間](https://live.bilibili.com/2808861) 每晚直播敲代碼，近期很長一段時間應該都是在寫本軟體~  

技術群（舟無關、禁水）：[内卷地狱！(QQ 群)](https://jq.qq.com/?_wv=1027&k=ypbzXcA2)  
開發者群：[QQ 群](https://jq.qq.com/?_wv=1027&k=JM9oCk3C)  

如果覺得軟體對你有幫助，幫忙點個 Star 吧！~（網頁最上方右上角的小星星），這就是對我們最大的支持了！

<!-- markdownlint-disable-file MD041 -->
