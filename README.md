# AppTeam - App 製作顧問與開發團隊

App 互動開發的完整解決方案（Claude Code Skill）

## 簡介

AppTeam 是專為 App 開發設計的顧問與協作團隊，涵蓋從需求分析、UI/UX 設計、開發實作到測試交付的完整流程。特別適合兒童英文學習 App、互動式教材、故事繪本等教育類應用程式。

## 📱 支援平台

- **iOS** - iPhone / iPad
- **Android** - 手機 / 平板
- **跨平台** - React Native / Flutter / PWA

## 🎯 適用場景

| 類型 | 說明 |
|------|------|
| **兒童英文學習 App** | 互動式單字、發音、遊戲學習 |
| **互動式教材 App** | 數位課程、練習題、測驗系統 |
| **故事繪本 App** | 有聲書、動畫繪本、互動故事 |
| **學習遊戲 App** | 教育遊戲、益智遊戲、闖關學習 |

## 📁 團隊結構

```
AppTeam/
├── SKILL.md           主要技能定義
├── agents/            團隊成員
│   ├── app-pm.md      專案經理 - 需求分析與流程協調
│   ├── app-developer.md 開發工程師 - 實作與整合
│   └── app-qa.md      QA 測試 - 功能測試與品質把關
├── skills/            共用技能
│   └── (子技能定義)
└── rules/             開發規範
    └── (團隊規則)
```

## 👥 團隊成員

### 1. App PM (專案經理)

**職責**:
- 需求確認與分析
- 技術方案選擇
- 流程協調與進度管理
- 功能規格撰寫

**擅長**:
- 平台選擇建議（iOS/Android/跨平台）
- 功能優先級排序
- 成本與時程評估

### 2. App Developer (開發工程師)

**職責**:
- App 實作開發
- UI/UX 實現
- API 整合
- 效能優化

**技術棧**:
- React Native / Flutter
- Swift (iOS) / Kotlin (Android)
- REST API 整合
- 本地儲存與快取

### 3. App QA (測試工程師)

**職責**:
- 功能測試
- 裝置相容測試
- 效能測試
- Bug 回報與追蹤

**測試範圍**:
- 不同裝置尺寸
- 不同作業系統版本
- 網路狀況測試
- 使用者體驗測試

## 🚀 工作流程

### 階段 1: 需求確認

```
✓ 確認目標平台（iOS/Android/兩者）
✓ 確認技術方案（原生/跨平台）
✓ 確認功能需求
✓ 確認素材清單（圖片、音檔、文案）
```

### 階段 2: 規格設計

```
✓ UI/UX 設計
✓ 互動流程設計
✓ 技術架構設計
✓ API 規格（如需要）
```

### 階段 3: 開發實作

```
✓ 畫面開發
✓ 互動功能實作
✓ API 整合
✓ 資料儲存
```

### 階段 4: 測試驗證

```
✓ 功能測試
✓ 裝置測試
✓ 效能測試
✓ Bug 修正
```

### 階段 5: 交付部署

```
✓ 測試通過確認
✓ 打包輸出
✓ App Store / Google Play 上架（可選）
✓ 文件交付
```

## 💡 使用方式

### 方式一：全域安裝

```bash
# 安裝到全域 skills
ln -s ~/AgentProjects/AppTeam ~/.claude/skills/app-produce-consult
```

### 方式二：專案內使用

```bash
# 複製到專案的 .claude/skills/
cp -r ~/AgentProjects/AppTeam /path/to/project/.claude/skills/app-produce-consult
```

### 方式三：直接呼叫

在 Claude Code 中：
```
/app-produce-consult
```

## 📖 使用範例

### 範例 1: 製作兒童英文單字學習 App

```
使用者: "我想做一個兒童英文單字學習 App，有圖片、發音、小遊戲"

AppTeam 流程:
1. PM 確認需求：平台（iOS/Android）、單字數量、遊戲類型
2. Developer 規劃技術：React Native + 音檔播放
3. 設計 UI：單字卡片、翻牌遊戲、配對遊戲
4. 開發實作：畫面 + 互動 + 音效
5. QA 測試：功能、相容性、效能
6. 交付：可安裝的 APK/IPA
```

### 範例 2: 互動式繪本 App

```
使用者: "我有一個故事繪本，想做成互動式 App"

AppTeam 流程:
1. PM 確認：頁數、互動方式（點擊動畫、有聲朗讀）
2. Developer 規劃：翻頁效果、音訊播放、動畫觸發
3. 設計：頁面佈局、互動熱區、動畫效果
4. 開發：繪本閱讀器、音訊整合、互動功能
5. QA 測試：翻頁流暢度、音訊同步、互動回饋
6. 交付：完整 App 包
```

## 🔗 依賴工具

本專案可能需要以下 AITools（請從 [AITools](https://github.com/pin0513/AITools) 安裝）：

- `dev-team-pm` - 專案管理方法論
- `dev-team-qa` - QA 測試標準
- `user-story-mastery` - 需求拆解

安裝方式：
```bash
ln -s ~/AgentProjects/AITools/skills/dev-team-pm ~/.claude/skills/dev-team-pm
ln -s ~/AgentProjects/AITools/skills/dev-team-qa ~/.claude/skills/dev-team-qa
```

## 📊 技術規格

- **前端框架**: React Native / Flutter / Swift / Kotlin
- **狀態管理**: Redux / MobX / Provider
- **資料儲存**: AsyncStorage / SQLite / Realm
- **網路請求**: Axios / Fetch API
- **測試工具**: Jest / Detox / Appium

## 📝 注意事項

1. **平台差異**: iOS 和 Android 有不同的設計規範和技術限制
2. **效能考量**: App 需注意記憶體使用和啟動速度
3. **裝置相容**: 需測試不同尺寸和系統版本
4. **資料安全**: 兒童 App 需特別注意隱私保護

## 授權

Private - 個人使用

## 維護者

Paul Huang (@pin0513)

---

**專案位置**: `/Users/paul_huang/AgentProjects/AppTeam`
**GitHub**: https://github.com/pin0513/AppTeam
**建立日期**: 2026-02-08
**來源**: 從 AITools/skills/teams/app-produce-consult 獨立
