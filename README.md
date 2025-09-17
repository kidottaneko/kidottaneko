# Takumi Ino / kidottaneko
**顧客課題 → 設計 → IaC → 監視/運用 → ふり返り** まで自分の手で回すことを目標に、サーバーレス構成とTerraformを中心に学習・実装しています。

## 📌 ポートフォリオ（就活用）
- **メイン**：[`sw-portfolio-2025`](https://github.com/kidottaneko/sw-portfolio-2025)  
  - 取り組み中テーマ：**API Gateway + Lambda + DynamoDB** でのミニ移行  
  - IaC：Terraform、監視：CloudWatch、コスト：Cost Explorerで可視化  
  - ドキュメント：`runbook.md`（運用手順） / `postmortem.md`（障害ふり返り） / `proposal/`（提案書）
 
  ## 🔧 Tech Focus
- **AWS**：API Gateway / Lambda / DynamoDB / CloudWatch / IAM / WAF(検討)
- **IaC**：Terraform（最小権限・環境分離・アラート設定）
- **Design**：SLO/SLI（p95レイテンシ・可用性）と **コスト前提の設計判断**
- **Dev**：Node.js or Python（Lambda）、GitHub Actions（必要に応じて）

---

## 🚀 いま進めていること
- [ ] 最小API（Lambda+APIGW）をデプロイ  
- [ ] Terraform化（VPC, IAM, Logs, Alarms）  
- [ ] **提案書5枚**（As-Is/To-Be/Why AWS/移行手順&リスク/概算コスト）  
- [ ] 監視ダッシュボードと**SLO/SLI**の明文化  
- [ ] 記事 #1：サーバーレス移行で運用/コストがどう変わるか（実測）

---

## 📅 進捗ログ（Daily）
- 2025-09-17: プロフィールREADME初版／`sw-portfolio-2025`作成／説明会申込待ち
- 2025-09-18: （例）最小Lambda/APIを手デプロイ → 動作確認
- 2025-09-19: （例）Terraform雛形作成 → VPC/IAM/Logs


---

## 🎯 志向
- 「サービス名の暗唱」ではなく **顧客価値**と**運用しやすさ**で設計判断をする  
- 障害を**是正学習**につなげる（Runbook整備、監視指標の見直し、コスト監視）

---

## 📫 Contact
- GitHub: https://github.com/kidottaneko
