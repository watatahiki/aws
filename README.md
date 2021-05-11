## アジェンダ
- AWS サービスの経験・できること一覧
- twitter
- エンジニアブログ

## AWS サービスの経験・できること一覧

### 分析
- Athena
	- ALB・CloudFront・WAF を含む S3 に格納しているログのテーブル作成・検索が可能
	- パーティション分割は Glue にて自動化
- Kinesis
	- Kinesis Data Firehose を使用して WAF ログ を S3 に格納
- QuickSight
	- ALB・CloudFront ログの可視化経験あり
- Glue
	- Glue クローラを使用して S3 バケットの WAF ログをパーティション分割した経験あり

### AWS コスト管理
- Savings Plans
	- 対象・メリット・設定方法などを理解

### コンピューティング
- EC2
	- 複数のサービスにて構築・運用経験あり
	- 各種サーバ (Web・AP・DB など) の構築が可能
	- インスタンスタイプ (arm など) によるメリット・デメリットも理解

### コンテナ
- ECR
	- 構築・運用経験あり
	- ECS のコンテナレジストリとして使用
- ECS
	- 複数のサービスにて構築・運用経験あり
	- ECS on EC2 を主に使用し、EC2 側の設定内容も把握
- Fargate
	- ※ 現在、挑戦中

### データベース
- Aurora
	- 複数のサービスにて構築・運用経験あり
	- Aurora のバージョンアップなども実施経験あり
- ElastiCache
	- 複数のサービスにて構築・運用経験あり
- RDS
	- 複数のサービスにて構築・運用経験あり
	- オンプレミスから RDS への移行も経験

### デベロッパーツール
- CodeBuild
	- ソース・ECS のデプロイ時に構築・使用経験あり
- CodeCommit
	- ソースのデプロイ時に構築・使用経験あり
- CodeDeploy
	- ソース・ECS のデプロイ時に構築・使用経験あり
- CodePipeline
	- ソース・ECS のデプロイ時に構築・使用経験あり

### マネジメントとガバナンス
- CloudWatch
	- 複数のサービスでの運用や、監視内製化の構築経験あり
	- ダッシュボード・アラームの構築は CloudFormation を使用
- Auto Scaling
	- EC2・RDS のオートスケーリング設定経験あり
- Chatbot
	- GuardDuty の結果や CloudWatch アラームの内容、スロークエリなど様々な情報を Slack へ通知設定
- CloudFormation
	- CloudFormation で複数の AWS サービスの構築経験あり
	- ソースは GitHub に上げている
- CloudTrail
	- ※ 現在、挑戦中
- Organizations
	- 複数アカウントでの運用経験あり
- Personal Health Dashboard
	- ※ 現在、挑戦中

### ネットワーキングとコンテンツ配信
- VPC
	- 複数のサービスにて構築・運用経験あり
- CloudFront
	- 複数のサービスにて構築・運用経験あり
	- パフォーマンスチューニングにて実施
- Route 53
	- 複数のサービスにてレコードの登録・管理経験あり
	- Route 53 ヘルスチェックも経験
- Transit Gateway
	- 複数のサービスにて構築・運用経験あり
- ELB
	- 複数のサービスにて構築・運用経験あり
	- 主に ALB を使用、Classic も過去経験あり

### セキュリティ、アイデンティティ、コンプライアンス
- IAM
	- 複数のサービスにて設定・運用経験あり
	- IAM ユーザに関してはできるだけ作成せず AssumeRole を持ちいる形にしている
- Detective
	- 複数のサービスにて導入・運用経験あり
- GuardDuty
	- 複数のサービスにて導入・運用経験あり
	- 結果は SNS にて Slack へ通知
- ACM
	- 複数のサービスにて導入・運用経験あり
	- サーバ配置型 SSL 証明書からの移行も経験
- KMS
	- 複数のサービスにて導入・運用経験あり
- Security Hub
	- ※ 現在、挑戦中
- Single Sign-On
	- 運用経験あり
	- 二段階認証の導入を実施中
- WAF
	- 複数のサービスにて設定・運用経験あり
	- 手動でも CloudFormation でも設定可能

### サーバーレス
- Lambda
	- 複数のサービスにて導入・運用経験あり
	- 主に画像リサイズを行う際に使用していたが、個人的に設定したものは EC2 や RDS の自動起動・停止など
- SNS
	- 複数のサービスにて導入・運用経験あり
	- CloudFormation での作成も実施
- API Gateway
	- 複数のサービスにて導入・運用経験あり
	- 主に Lambda を API として呼び出す際に使用

### ストレージ
- S3
	- 複数のサービスにて導入・運用経験あり
	- ライフサイクルポリシーを用いたコスト削減なども実施
- EBS
	- 複数のサービスにて導入・運用経験あり
	- ライフサイクルポリシーを用いたコスト削減なども実施
- EFS
	- 特定のサービスにて導入・運用経験あり
	- WordPress を扱うサービスに導入
- Backup
	- 複数のサービスにて導入・運用経験あり
	- EC2・RDS のバックアップ一元化に使用

## twitter
https://twitter.com/watatahiki

## エンジニアブログ
https://engineers.weddingpark.co.jp/author/watahiki/
