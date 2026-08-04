# RLS-001 Evidence Card Standard

- **Document ID**: RLS-001
- **Version**: 1.0
- **Status**: Approved
- **Owner**: AI Transformation Research Lab
- **Last Updated**: 2026-08-05

---

# 1. Purpose

本標準は、Research Question (RQ) を支えるEvidence（根拠）の記録方法を統一することを目的とする。

Evidenceは、Microsoft公式情報、実機検証、コミュニティ情報などを一貫した形式で記録し、Research Lab全体で再利用できる知識資産とする。

---

# 2. Scope

本標準は、すべてのResearch Question (RQ) に適用する。

対象とするEvidenceは以下を含む。

- Microsoft Docs
- Microsoft Learn
- Microsoft Support
- Microsoft Build / Ignite
- Microsoft公式ブログ
- Microsoft公式動画
- 実機検証
- Community記事（Zenn, Qiita等）
- AIによる補助的な説明

---

# 3. Evidence Card Template

```markdown
## E-XXX

### Source

### Title

### URL

### Retrieved

### Reliability

### Key Point

### Impact
```

---

# 4. Field Definitions

## Source

情報源。

例

- Microsoft Docs
- Microsoft Learn
- Microsoft Support
- Microsoft Build
- Practical Verification

---

## Title

ページまたは資料の正式名称。

---

## URL

参照元URL。

実機検証の場合は「N/A」とする。

---

## Retrieved

Evidenceを取得・確認した日付を記録する。

日付は日本標準時（JST）を基準とし、

ISO 8601形式（YYYY-MM-DD）で記載する。

---

## Reliability

情報の信頼度。

| Level | Description |
|--------|-------------|
| A | Microsoft Official Documentation / Product Behavior |
| B | Microsoft Learn |
| C | Microsoft Official Blog / Microsoft Build / Ignite |
| D | Practical Verification |
| E | Community |
| F | AI-generated explanation |

---

## Key Point

**事実のみ**を記載する。

記載してよい内容

- Microsoftが明示している仕様
- 実機で確認できた事実
- ページに書かれている内容

記載しない内容

- 推測
- 考察
- 意見

---

## Impact

Research Questionへの影響を記載する。

例

- 仮説を支持する
- 仮説を修正する必要がある
- 新たな検証項目が見つかった

ここでは考察を書いてよい。

---

# 5. Writing Rules

Evidence Cardは

- 短く
- 客観的に
- 再利用可能に

記述する。

---

# 6. Principles

Evidence Cardは

「事実」と「解釈」を明確に分離する。

Key Pointには事実のみを書く。

ImpactにはResearch Questionへの影響を書く。

---

# 7. Example

## E-001

### Source

Microsoft Support

### Title

How Microsoft 365 Copilot Chat history works

### URL

https://support.microsoft.com/

### Retrieved

2026-08-05

### Reliability

A (Microsoft Official)

### Key Point

- Copilot Chatはチャット履歴を保持する。
- 応答生成時に履歴を利用する場合がある。

### Impact

RQ-001では、新しいチャットでも履歴が推論に利用される可能性を考慮する必要がある。

---

# 8. Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0 | 2026-08-05 | Initial Release |
