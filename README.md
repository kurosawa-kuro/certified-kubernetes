# certified-kubernetes

**Kubernetes 認定試験（日本語版）の概要まとめ**

| 試験名                                                         | オンラインで受験可 | 日本語で受験可<sup>†</sup>                             | 公式トレーニングコース                                                                    | 事前合格必須資格                                          | 選択式問題 | 実技（CLI／コーディング）                                          | 受験費用<sup>‡</sup>                                                     | 主な出題範囲（ドメイン比率）                                                                                                                                      |
| ----------------------------------------------------------- | --------- | ----------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------- | ----- | ------------------------------------------------------- | -------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CKAD-JP**<br>（Certified Kubernetes Application Developer） | ✔ リモート監督  | ✔ 試験 UI 切替可 ([Linux Foundation - Education][1]) | LFD259 *Kubernetes for Developers* など ([Linux Foundation - Education][1])      | なし                                                | ✕     | ✔ （2 時間・パフォーマンスベース） ([Linux Foundation - Education][1]) | 約 71,000 円※／US \$490 ([LPI日本][2], [Linux Foundation - Education][1]) | アプリ設計 & ビルド 20%<br>デプロイ 20%<br>可観測性 & 保守 15%<br>環境・構成・セキュリティ 25%<br>サービス & NW 20% ([Linux Foundation - Education][1])                               |
| **CKA-JP**<br>（Certified Kubernetes Administrator）          | ✔         | ✔ ([Linux Foundation - Education][3])           | LFS258-JP *Kubernetes Fundamentals* など ([Linux Foundation - Education][3])     | なし                                                | ✕     | ✔ （2 時間・実技） ([Linux Foundation - Education][3])         | 約 71,000 円※／US \$490 ([LPI日本][2], [Linux Foundation - Education][3]) | クラスタ構成/インストール 25%<br>ワークロード & スケジューリング 15%<br>ストレージ 10%<br>サービス & NW 20%<br>トラブルシューティング 30% ([Linux Foundation - Education][3])                     |
| **CKS-JP**<br>（Certified Kubernetes Security Specialist）    | ✔         | ✔ ([Linux Foundation - Education][4])           | LFS260 *Kubernetes Security Essentials* など ([Linux Foundation - Education][4]) | **CKA 合格が必須** ([Linux Foundation - Education][4]) | ✕     | ✔ （2 時間・実技） ([Linux Foundation - Education][4])         | 約 71,000 円※／US \$490 ([LPI日本][2], [Linux Foundation - Education][4]) | クラスタ設定 15%<br>クラスタ強化 15%<br>システム強化 10%<br>マイクロサービス脆弱性最小化 20%<br>サプライチェーンセキュリティ 20%<br>監視・ロギング & ランタイムセキュリティ 20% ([Linux Foundation - Education][4]) |

<sup>†</sup>試験内容は日本語表示に切替可能ですが、試験監督（プロクター）は英語で対応します。 <sup>‡</sup>Linux Professional Institute Japan（LPI-Japan）経由の国内価格が 71,000 円（税込）で案内されています。Linux Foundation公式サイトでは US \$490（税込）と表示されており、為替や税込条件により実際の支払い額が前後します。 ([LPI日本][2], [Linux Foundation - Education][1], [Linux Foundation - Education][3], [Linux Foundation - Education][4])

### 補足ポイント

* **形式**：いずれも Kubernetes クラスタ上でタスクを実行するパフォーマンスベース試験（YAML 記述・`kubectl`／`kubeadm` 操作など）。マルチプルチョイス問題は出題されません。
* **受験環境**：自宅 PC から受験可能。Web カメラ／マイクによるリモート監督、シングルモニタ必須。
* **再受験**：全試験とも *1 回* の無償再受験（リテイク）権が付属。
* **バージョン**：2025-05-16 時点で **Kubernetes v1.32** ベース。四半期ごとに最新マイナーバージョンへアップデートされます。 ([Linux Foundation - Education][1], [Linux Foundation - Education][3], [Linux Foundation - Education][4])
* **学習リソース**：Linux Foundation 公式 eLearning、Killer.sh 模擬試験（2 回まで）、および公開カリキュラム/ハンドブックが提供されています。

これで試験選択や学習計画の俯瞰がしやすくなるはずです。必要に応じて、各試験ドメインの詳細シラバスや模擬環境構築手順もご案内できますので、気軽にお知らせください！

[1]: https://training.linuxfoundation.org/ja/certification/certified-kubernetes-application-developer-ckad-jp/ "認定Kubernetesアプリケーション開発者 (CKAD-JP) - Linux Foundation - Education"
[2]: https://lpi.or.jp/k8s/?utm_source=chatgpt.com "Kubernetes技術者認定 （CKA-JP／CKAD-JP／CKS-JP／KCNA-JP）"
[3]: https://training.linuxfoundation.org/ja/certification/certified-kubernetes-administrator-cka-jp/ "認定Kubernetes管理者 (CKA-JP) - Linux Foundation - Education"
[4]: https://training.linuxfoundation.org/ja/certification/certified-kubernetes-security-specialist-cks-jp/ "認定Kubernetesセキュリティスペシャリスト (CKS-JP) - Linux Foundation - Education"
