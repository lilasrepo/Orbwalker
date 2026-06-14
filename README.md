# Orbwalker（繁中移植版 · TC12） / Traditional-Chinese Port

> S P A C E　G L I D I N G（讀條中也能走位）。<br>
> S P A C E G L I D I N G.

**繁體中文**：這是 **[Orbwalker](https://github.com/PunishXIV/Orbwalker)** 的繁體中文客戶端移植版，對應 **FFXIV 7.1 / yanmucorp Dalamud API12（.NET 9）**。本專案僅做相容性移植，**非官方、非原作維護**；所有原始功能與設計著作權歸原作者 **кайт машина (Puni.sh)**。

**English**: A Traditional-Chinese-client port of **[Orbwalker](https://github.com/PunishXIV/Orbwalker)** targeting **FFXIV 7.1 / yanmucorp Dalamud API12 (.NET 9)**. Compatibility port only — **unofficial and not maintained by the original author**. All original work © **кайт машина (Puni.sh)**.

---

## 這是什麼 / About

在施法讀條期間鎖定角色位移，讓施法者在戰鬥中達到最大輸出時間（uptime）。

Locks player movement while casting, maximising caster uptime throughout a fight.

## 安裝 / Installation

**繁體中文**
1. 使用 **XIVTCLauncher** 啟動繁體中文客戶端。
2. 遊戲內輸入 `/xlsettings` → 切到 **Experimental** 分頁 → **Custom Plugin Repositories（自訂插件庫）**。
3. 貼上下列網址並按 **+** 儲存：
   ```
   https://raw.githubusercontent.com/lilasrepo/DalamudPlugins/main/pluginmaster.json
   ```
4. 輸入 `/xlplugins`，搜尋 **Orbwalker (TC12)** → 安裝 → 啟用。

**English**
1. Launch the Traditional-Chinese client with **XIVTCLauncher**.
2. In-game, type `/xlsettings` → **Experimental** tab → **Custom Plugin Repositories**.
3. Add this URL and save with **+**:
   ```
   https://raw.githubusercontent.com/lilasrepo/DalamudPlugins/main/pluginmaster.json
   ```
4. Type `/xlplugins`, search **Orbwalker (TC12)** → Install → Enable.

## 對應版本 / Compatibility

| 項目 / Item | 版本 / Version |
|---|---|
| 遊戲 / Game | FFXIV 7.1（繁中客戶端 / TC client） |
| Dalamud | yanmucorp API12（.NET 9） |
| 移植自上游 / Ported from upstream | v1.0.1.10 |

## 原作與授權 / Credits & License

本專案 fork 自 **[PunishXIV/Orbwalker](https://github.com/PunishXIV/Orbwalker)**，授權沿用上游；所有原始功能著作權歸 **кайт машина (Puni.sh)**。<br>
Forked from **[PunishXIV/Orbwalker](https://github.com/PunishXIV/Orbwalker)**. License follows upstream; all original work © **кайт машина (Puni.sh)**.

## 免責聲明 / Disclaimer

第三方插件，使用風險自負。**移植相關問題請回報到本 repo 的 Issues，請勿打擾上游原作者。**<br>
Third-party plugin — use at your own risk. **For port-specific issues please open an Issue here; do not contact the upstream author.**
