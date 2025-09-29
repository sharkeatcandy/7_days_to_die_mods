# Casino Coin Reward Multiplier x20

## 描述
這個 MOD 將 7 Days to Die 中所有任務奖励的 Casino Coin（賭場币）數量乘以 20 倍，涵蓋所有類型的任務。

## 功能
- 將所有任務中的 casinoCoin 獎勵乘以 20
- 包括所有等级的 Fetch、Clear、Infested Clear 任務
- 包括 Restore Power 和 Fetch & Clear 混合任務
- 包括 Buried Supplies 任務
- 包括所有測試任務和等級完成獎勵
- 總共修改了 **54 個任務** 的 casinoCoin 獎勵

## 完整獎勵變化表

### Fetch 任務 (6項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 1 Fetch | 100 | 2,000 |
| Tier 2 Fetch | 200 | 4,000 |
| Tier 3 Fetch | 300 | 6,000 |
| Tier 4 Fetch | 500 | 10,000 |
| Tier 5 Fetch | 1,000 | 20,000 |
| Tier 6 Fetch | 3,000 | 60,000 |

### Clear 任務 (6項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 1 Clear | 400 | 8,000 |
| Tier 2 Clear | 500 | 10,000 |
| Tier 3 Clear | 800 | 16,000 |
| Tier 4 Clear | 1,000 | 20,000 |
| Tier 5 Clear | 2,000 | 40,000 |
| Tier 6 Clear | 4,000 | 80,000 |

### Infested Clear 任務 (5項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 2 Clear Infested | 1,000 | 20,000 |
| Tier 3 Clear Infested | 2,000 | 40,000 |
| Tier 4 Clear Infested | 3,000 | 60,000 |
| Tier 5 Clear Infested | 4,000 | 80,000 |
| Tier 6 Clear Infested | 6,000 | 120,000 |

### Restore Power 任務 (3項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 2 Restore Power | 800 | 16,000 |
| Tier 3 Restore Power | 1,500 | 30,000 |
| Tier 4 Restore Power | 2,000 | 40,000 |

### Fetch & Clear 任務 (5項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 2 Fetch Clear | 700 | 14,000 |
| Tier 3 Fetch Clear | 1,000 | 20,000 |
| Tier 4 Fetch Clear | 1,500 | 30,000 |
| Tier 5 Fetch Clear | 2,000 | 40,000 |
| Tier 6 Fetch Clear | 5,000 | 100,000 |

### Buried Supplies 任務 (3項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 1 Buried Supplies | 250 | 5,000 |
| Tier 2 Buried Supplies | 500 | 10,000 |
| Tier 3 Buried Supplies | 1,000 | 20,000 |

### 測試任務 (8項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Test Sleepers | 350 | 7,000 |
| Test Sleepers Infested | 350 | 7,000 |
| Test Fetch | 350 | 7,000 |
| Test Fetch Sleep | 350 | 7,000 |
| Test Fetch Infested | 350 | 7,000 |
| Test Hidden Sleep | 350 | 7,000 |
| Test Restore Power | 350 | 7,000 |
| Test Turn In | 200 | 4,000 |

### 等級完成獎勵 (6項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 1 Complete | 2,000 | 40,000 |
| Tier 2 Complete | 2,000 | 40,000 |
| Tier 3 Complete | 2,000 | 40,000 |
| Tier 4 Complete | 2,000 | 40,000 |
| Tier 5 Complete | 2,000 | 40,000 |
| Tier 6 Complete | 2,000 | 40,000 |

### 管理員測試任務 (6項)
| 任務 | 原始值 | 新值 |
|------|--------|------|
| Tier 1 Test Turn In | 100 | 2,000 |
| Tier 2 Test Turn In | 200 | 4,000 |
| Tier 3 Test Turn In | 300 | 6,000 |
| Tier 4 Test Turn In | 500 | 10,000 |
| Tier 5 Test Turn In | 1,000 | 20,000 |
| Tier 6 Test Turn In | 3,000 | 60,000 |

## 安裝方法
1. 將整個 `Casino_Coin_Reward_Multiplier` 資料夾複製到游戲的 `Mods` 目錄中
2. 啟動游戲即可生效

## 文件結構
```
Casino_Coin_Reward_Multiplier/
├── ModInfo.XML          # MOD 信息文件
├── Config/
│   └── quests.xml      # 任務配置修改文件
└── README.md           # 說明文件
```

## 技術細節
- 使用 XPath 語法精確定位每個任務的 casinoCoin 獎勵
- 支持所有任務類型：Fetch、Clear、Infested、Restore Power、混合任務等
- 包含測試任務和等級完成獎勵
- 總共修改 54 個不同的任務獎勵

## 注意事項
- 此 MOD 僅修改任務獎勵中的 Casino Coin 數量
- 不影響其他獎勵物品或游戲機制
- 與防作弊系統兼容（SkipWithAntiCheat=true）
- 建議在新游戲中使用以獲得最佳體驗
- 所有獎勵都精確乘以 20 倍

## 版本信息
- 版本：1.0
- 作者：Shark
- 適用游戲版本：7 Days to Die V1.0+
- 修改任務數量：54 個任務

## 卸載方法
刪除 `Mods/Casino_Coin_Reward_Multiplier` 資料夾即可