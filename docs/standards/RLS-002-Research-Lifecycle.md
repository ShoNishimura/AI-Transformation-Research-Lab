# RLS-002 Research Lifecycle

- **Document ID**: RLS-002
- **Version**: 1.0
- **Status**: Approved
- **Owner**: AI Transformation Research Lab
- **Last Updated**: 2026-08-05

---

# 1. Purpose

本標準は、Research Question（RQ）のライフサイクルを定義し、
Research Labにおける調査・検証・知識化・実務適用・公開までの
一貫したプロセスを標準化することを目的とする。

---

# 2. Scope

本標準は、すべてのResearch Question（RQ）に適用する。

---

# 3. Lifecycle

すべてのResearch Questionは、以下のライフサイクルに従う。

```

Draft RQ
↓

Official Research
↓

Verification

↓

Handbook

↓

Business Applied

↓

Published

```

---

# 4. Stage Definitions

## ① Draft RQ

### Purpose

研究テーマ（Research Question）を定義する。

### Activities

- GitHub Issueを作成
- 背景を整理
- 仮説を作成
- 検証項目を整理

### Exit Criteria

Issueが作成され、
調査対象が明確になっていること。

---

## ② Official Research

### Purpose

Microsoft公式情報を調査する。

### Activities

- Microsoft Learn
- Microsoft Docs
- Microsoft Support
- Microsoft Build / Ignite
- Microsoft公式ブログ

Evidence Card（RLS-001）を追加する。

### Exit Criteria

少なくとも1件以上の
Microsoft公式Evidenceが登録されていること。

---

## ③ Verification

### Purpose

実機検証またはPoCを実施する。

### Activities

- 実機確認
- Python検証
- Microsoft 365検証
- Copilot検証
- AI Agent検証

Evidence Cardを追加する。

### Exit Criteria

仮説について、
実機による検証結果が整理されていること。

---

## ④ Handbook

### Purpose

検証結果を再利用可能な知識へ整理する。

### Activities

- Markdownへ知識を整理
- Handbookへ反映
- 関連RQをリンク

### Exit Criteria

第三者が理解できるレベルで
知識が体系化されていること。

---

## ⑤ Business Applied

### Purpose

実務へ適用する。

### Activities

- PoC
- 業務改善
- 社内展開
- フィードバック収集

### Exit Criteria

実務で利用され、
効果または課題が確認されていること。

---

## ⑥ Published

### Purpose

社会へ還元する。

### Activities

- GitHub公開
- Zenn記事
- LT
- Community発表

### Exit Criteria

公開可能な形で成果が発信されていること。

---

# 5. GitHub Project Mapping

| Lifecycle | GitHub Project |
|------------|----------------|
| Draft RQ | 💡 Draft RQ |
| Official Research | 📚 Official Research |
| Verification | 🧪 Verification |
| Handbook | 📖 Handbook |
| Business Applied | 🏢 Business Applied |
| Published | 🌍 Published |

---

# 6. Issue Management

Research Questionは
GitHub IssueをSingle Source of Truthとする。

Issue本文には、

- Background
- Hypothesis
- Evidence一覧
- Current Conclusion
- Next Action

を管理する。

Evidenceの詳細は
Issueコメントとして追加する。

---

# 7. Completion Criteria

Research Questionは
Publishedまで完了した時点で
IssueをCloseする。

Closed Issueは
Research Labの知識資産として保存される。

---

# 8. Principles

Research Lifecycleは
Research Lab Charterに従う。

特に以下を遵守する。

- Official First
- Evidence Before Opinion
- Verify Whenever Possible
- Single Source of Truth
- Reusable Knowledge
- Business First
- Share Responsibly

---

# 9. Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0 | 2026-08-05 | Initial Release |
