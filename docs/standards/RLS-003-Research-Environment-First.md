# RLS-003 研究環境標準

Version: 1.0

Status: Approved

---

## 1. 目的

Research Lab における研究環境を標準化し、研究結果の再現性、安全性および独立性を確保する。

---

## 2. 適用範囲

本規約は、Research Lab リポジトリで実施するすべての研究活動に適用する。

対象例

- Microsoft 365
- Microsoft 365 Copilot
- SharePoint
- OneDrive
- Exchange Online
- Microsoft Teams
- Microsoft Graph
- Power Platform
- その他 Research Lab で利用する Microsoft サービス

---

## 3. 基本方針

Research Lab の研究は、専用の Research Tenant を使用して実施する。

研究環境は、業務環境および個人利用環境から論理的に独立していることを原則とする。

---

## 4. 研究環境

Research Lab では、以下の環境を標準環境とする。

| 項目 | 内容 |
|------|------|
| Microsoft 365 テナント | Research Tenant |
| ライセンス | Microsoft 365 Business Standard |
| AI | Microsoft 365 Copilot |
| 認証 | Microsoft Entra ID |
| ストレージ | OneDrive / SharePoint |
| メール | Exchange Online |
| コラボレーション | Microsoft Teams |

研究に必要なライセンスおよびサービスは、研究目的に応じて追加できる。

---

## 5. 運用ルール

- 研究は Research Tenant を使用して実施する。
- 業務環境を主たる研究環境として使用しない。
- 実験は可能な限り再現可能な状態で実施する。
- 実験条件は LAB または Verification に記録する。
- 研究結果は Handbook へ反映する。
- 公開する内容は、機密情報および個人情報を含まないことを確認する。

---

## 6. セキュリティ

- 機密情報を研究目的で使用しない。
- 業務データを無断で Research Tenant へ持ち込まない。
- 公開前に個人情報および組織情報を確認する。
- Microsoft の利用規約およびライセンス条件を遵守する。

---

## 7. 関連文書

- RLS-000 ドキュメント作成規約
- RLS-001 エビデンスカード標準
- RLS-002 研究ライフサイクル
- GLOSSARY

---

## 8. 改訂

改訂履歴は GitHub の変更履歴を正本とする。

本規約の改訂は、Research Lab の合意のもとで実施する。
