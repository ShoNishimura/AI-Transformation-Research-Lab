# AI Transformation Research Lab

> **Microsoft 365 Copilot を中心とした AI 活用の研究・検証・知識体系化を行う Research Lab**

---

# Research Lab とは

本リポジトリは、**AI Transformation Research Lab** の活動を管理するためのリポジトリです。

Research Lab では、Microsoft 365 Copilot を中心とした AI 活用に関する知見を、**公式情報**と**再現可能な実験**に基づいて蓄積・検証・体系化します。

研究は、Research Question（RQ）を起点として、Evidence（E）、Experiment、Verification を通じて知識を構築し、その成果を Handbook として体系化します。

---

# 目的

Research Lab の目的は、次のとおりです。

- Microsoft 365 Copilot の理解を深める
- 公式情報を整理・評価する
- 再現可能な実験によって知見を検証する
- 検証結果を体系的な知識として蓄積する
- 社内外へ再利用可能な知識として発信する

---

# ディレクトリ構成

```text
docs/
├── charter/      # Research Lab の理念
├── glossary/     # 用語集
├── handbook/     # Handbook・LAB・Milestones
├── standards/    # Research Lab 標準
└── templates/    # 各種テンプレート
```

---

# アーキテクチャ

Research Lab は、役割ごとにドキュメントを分離して管理します。

| 種類 | 役割 | 例 |
|------|------|----|
| Charter | Research Lab の理念 | Charter |
| 規約 | Research Lab 全体の共通ルール | RLS-000 |
| 標準 | 個別領域の運用ルール | RLS-001～003 |
| テンプレート | ドキュメント作成用ひな形 | Evidence Card Template |
| 用語集 | 用語定義の正本 | GLOSSARY |
| Research Question | 研究課題 | RQ-001 |
| Evidence | 研究の根拠 | E-001 |
| LAB | 実験・作業記録 | LAB-001 |
| Handbook | 研究成果の体系化 | HANDBOOK |

---

# 命名方針

## ドキュメント名称

Research Lab では、役割に応じて名称を統一します。

| 種類 | 命名 |
|------|------|
| 全体ルール | ○○規約 |
| 個別ルール | ○○標準 |
| ひな形 | ○○テンプレート |
| 用語定義 | GLOSSARY |

## ファイル名

ファイル名は、管理IDと対象を組み合わせて命名します。

形式

```text
<管理ID>-<対象>.md
```

例

```text
RLS-000-Documentation.md
RLS-001-Evidence.md
RLS-002-Research-Process.md
RLS-003-Research-Environment.md

RQ-001-Copilot-Chat-Context.md
E-001-Chat-History.md

LAB-001-Research-Environment-Setup.md
```

---

# Research Lab 標準

Research Lab は、以下の標準に従って運営します。

| ID | 文書 |
|----|------|
| RLS-000 | ドキュメント作成規約 |
| RLS-001 | エビデンス標準 |
| RLS-002 | 研究プロセス標準 |
| RLS-003 | 研究環境標準 |

---

# 研究プロセス

Research Lab は、以下のプロセスに従って研究を進めます。

```text
Research Question
        │
        ▼
Evidence
        │
        ▼
Experiment
        │
        ▼
Verification
        │
        ▼
Conclusion
        │
        ▼
Handbook
```

---

# 基本原則

Research Lab は、次の原則に基づいて運営します。

- 公式情報を優先する
- 可能な限り一次情報を参照する
- 実験は再現可能であることを前提とする
- エビデンスに基づいて結論を導く
- 得られた知見は Handbook として体系化する

---

# ライセンス

本リポジトリは、適用されるライセンスに従います。
