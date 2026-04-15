# SE AI トレーニング 2026 — AI Co-innovation Lab 神戸

## 概要

GitHub Copilot / M365 Copilot / Microsoft Foundry を活用し、顧客シナリオに基づくプロトタイプを **2日間で設計・実装** する OpenHack 形式のトレーニングです。

| 項目 | 内容 |
|------|------|
| **日程** | 2026年4月22日（水）〜 23日（木）　各日 9:30〜17:00 |
| **場所** | AI Co-innovation Lab 神戸 |
| **対象者** | Solution Engineer（SE）12名 |
| **形式** | OpenHack（チーム対抗ハンズオン） |
| **チーム構成** | 3チーム × 4名 |

## 使用ツール

| ツール | 用途 |
|--------|------|
| **M365 Copilot** | リサーチ・要件定義 |
| **GitHub Copilot** | Vibe Coding によるプロトタイプ実装 |
| **Microsoft Foundry** | マルチエージェント構築 |
| **Foundry IQ**（オプション） | Agentic RAG |

## 2日間の流れ

### Day 1（4/22）— リサーチ → ヒアリング → 設計 → 実装開始

1. 座学セッション（GitHub Copilot / Microsoft Foundry / M365 Copilot）
2. チーム分け・シナリオ割り当て
3. M365 Copilot で業界リサーチ → ヒアリング準備
4. **顧客ロールプレイ**（トレーナーが顧客役）
5. 要件整理・アーキテクチャ設計 → 設計レビュー
6. Vibe Coding で実装開始

### Day 2（4/23）— 実装 → 発表

1. 実装の続き（Vibe Coding + Microsoft Foundry マルチエージェント）
2. 発表準備（M365 Copilot でデモ構成・ナレーション作成）
3. **発表会**（各チーム 25分：デモ 15分 + Q&A 10分）
4. 全体フィードバック & クロージング

## シナリオ一覧

各チームは以下のいずれかのシナリオを担当します。

| シナリオ | 業界 | テーマ | データ |
|----------|------|--------|--------|
| [**A — 製造業**](scenarios/scenario-a-manufacturing/) | 自動車部品製造 | インテリジェント品質管理エージェント | PDF / Excel / Word |
| [**B — 金融**](scenarios/scenario-b-finance/) | 証券（リサーチ部門） | 投資リサーチ自動化プラットフォーム | PDF / Web / Word |
| [**C — リテール/EC**](scenarios/scenario-c-retail/) | 総合ECプラットフォーム | AI カスタマーサポート自動化 | PDF / Excel / JSON |

## リポジトリ構成

```
├── README.md                        ← このファイル
├── docs/
│   ├── schedule.md                  Day 1 / Day 2 タイムテーブル
│   ├── team-structure.md            チーム構成・役割
│   └── tools.md                     使用ツールと事前準備
├── scenarios/
│   ├── README.md                    シナリオ共通の進め方
│   ├── scenario-a-manufacturing/    シナリオ A
│   │   ├── README.md
│   │   └── data/
│   ├── scenario-b-finance/          シナリオ B
│   │   ├── README.md
│   │   └── data/
│   └── scenario-c-retail/           シナリオ C
│       ├── README.md
│       └── data/
└── assets/
    ├── SE_AI_Training_Kobe_2026_Overview.pdf       概要資料
    ├── ScenarioA_ブリーフシート_参加者用.pdf         シナリオA概要資料
    ├── ScenarioB_ブリーフシート_参加者用.pdf         シナリオB概要資料
    └── ScenarioC_ブリーフシート_参加者用.pdf         シナリオC概要資料
```

## 関連ドキュメント

- [タイムテーブル](docs/schedule.md)
- [チーム構成・役割](docs/team-structure.md)
- [使用ツールと事前準備](docs/tools.md)
- [シナリオ共通ガイド](scenarios/README.md)
