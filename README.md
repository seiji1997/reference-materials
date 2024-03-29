# reference-materials
## title: AWS/Azure/Google Cloudサービス比較 2023.10

## Analytics
||AWS|Azure|GCP|
|---|---|---|---|
|データレイクへのクエリ|Amazon Athena|Azure Synapse Analytics/Azure Data Lake Analytics|BigQuery|
|検索|Amazon CloudSearch|Azure Cognitive Search|-|
|Hadoopクラスターの展開|Amazon EMR|HD Insight/Azure Databricks|Dataproc|
|Elasticsearchクラスターの展開|Amazon OpenSearch Service|Elasticsearch Service on Elastic Cloud|Elastic Cloud on GCP|
|ストリーミング処理|Amazon Kinesis|Azure Event Hubs|Cloud Dataflow|
|Kafkaクラスターの展開|Amazon Managed Streaming for Kafka|HDInsight|-|
|DWH|Amazon Redshift|Azure Synapse Analytics|Google BigQuery|
|BIサービス|Quick Sight|(Power BI)|Looker/Data Studio|
|データドリブンワークフロー|AWS Data Pipeline|Azure Data Factory|-|
|ETL|AWS Glue|Azure Data Factory|Cloud Data Fusion|
|データレイクの構築|AWS Lake Formation|-|-|
|データカタログ|AWS Glue|Azure Purview/Azure Data Catalog|Data Catalog|
|3rd-partyデータの購読|AWS Data Exchange|Azure Data Share|Analytics Hub|
|Data Preparation|AWS Glue DataBrew|-|Dataprep by Trifacta|
|金融サービス業界向けの分析|Amazon FinSpace|-|-|
|統合データガバナンス|Amazon DataZone|Azure Purview|-|
|データクリーンルーム|AWS Clean Rooms|-|-|

## Application Integration
||AWS|Azure|GCP|
|---|---|---|---|
|分散アプリケーションの作成|AWS Step Functions|Azure Logic Apps|Workflow|
|メッセージキュー|Amazon Simple Queue Service|Azure Queue Storage|Cloud Pub/Sub<br>Cloud Tasks|
|Pub/Sub|Amazon Simple Notification Service|Azure Service Bus|Cloud Pub/Sub|
|ActiveMQの展開|Amazon MQ|
|イベントの取り込みと配信|Amazon EventBridge|Event Grid|Eventarc|
|ジョブのスケジューリング|Amazon EventBridge|Azure Logic Apps|Cloud Scheduler|
|SaaSとのデータ連携|Amazon AppFlow|-|-|
|ワークフローオーケストレーション|Amazon Managed Workflows for Apache Airflow|Azure Data Factory|Cloud Composer|

## Blockchain
||AWS|Azure|GCP|
|---|---|---|---|
|ネットワークの作成と管理|Amazon Managed Blockchain|Azure Blockchain Service|-|
|台帳データベース|Amazon Quantum Ledger Database|-|-|
|アプリケーションの作成|-|Azure Blockchain Workbench|-|
|トークンの定義、作成、管理|-|Azure Blockchain Tokens|-|

## Business Applications
||AWS|Azure|GCP|
|---|---|---|---|
|Alexa|Alexa for Business|-|-|
|オンラインミーティング|Amazon Chime|(Office 365)|Google Workspace|
|通信機能をアプリケーションに実装|Amazon Chime SDK|Azure Communication Services|-|
|Eメール|Amazon WorkMail|(Office 365)|Google Workspace|
|No-Code|Amazon Honeycode|(PowerApps)|AppSheet|
|サプライチェーン管理|AWS Supply Chain|-|-|
|エンタープライズコミュニケーション|AWS Whickr|Azure Communication Services|-|

## Compute
||AWS|Azure|GCP|
|---|---|---|---|
|仮想マシン|Amazon EC2|Azure Virtual Machines|Compute Engine|
|オートスケール|Amazon EC2 Auto Scaling|Virtual Machine Scale Sets|Autoscaling|
|VPS|Amazon Lightsail|-|-|
|バッチコンピューティング|AWS Batch|Azure Batch|Batch|
|Webアプリケーションの実行環境|Amazon Elastic Beanstalk|Azure App Service|App Engine|
|Function as a Service|AWS Lambda|Azure Functions|Cloud Functions|
|サーバーレスアプリケーションのリポジトリ|AWS Serverless Application Repository|-|-|
|VMware環境の展開|VMware Cloud on AWS|Azure VMware Solution|Google Cloud VMware Engine|
|オンプレミスでの展開|AWS Outposts|Azure Stack|Google Distributed Cloud|
|5Gデバイス向けコンピューティング環境|AWS Wavelength|Azure private multi-access edge compute (MEC)|-|
|VMイメージ作成の自動化|EC2 Image Builder|Azure Image Builder|-|
|機密コンピューティング環境|AWS Nitro Enclaves|Azure Confidential Computing|Confidential VMs|
|空間シミュレーション|AWS SimSpace Weaver|-|-|

## Containers
||AWS|Azure|GCP|
|---|---|---|---|
|コンテナオーケストレーター|Amazon Elastic Container Service|Service Fabric|-|
|Kubernetes|Amazon Elastic Kubernetes Service|Azure Kubernetes Service|Google Kubernetes Engine|
|コンテナレジストリ|Amazon Elastic Container Registry|Azure Container Registry|Container Registry|
|インスタンス管理不要のコンテナ実行|AWS Fargate|Azure Container Instances|-|
|フルマネージドなコンテナ実行環境|AWS App Runner|Azure Container Apps|Cloud Run|
|既存アプリのコンテナ化|AWS App2Container|Azure Migrate|Migrate for Anthos|
|ハイブリッドクラウドの構築|Amazon ECS/EKS Anywhere|Azure Arc|Anthos|
|OpenShiftクラスターの展開|Red Hat OpenShift Service on AWS|Azure Red Hat OpenShift|-|

## Cost Financial Management
||AWS|Azure|GCP|
|---|---|---|---|
|使用状況の可視化|AWS Cost Explorer|Azure Cost Management|Cost Management|
|予算の管理|AWS Budgets|Azure Cost Management|Cloud Billing|
|リザーブドインスタンスの管理|Reserved Instance Reporting|Azure Cost Management|-|
|使用状況のレポート|AWS Cost & Usage Report|Azure Cost Management|Cloud Billing|
|Compute使用料の節約|Savings Plans|Azure Savings Plan|-|

## Customer Engagement
||AWS|Azure|GCP|
|---|---|---|---|
|コンタクトセンター|Amazon Connect|-|-|
|コンタクトセンターの分析|Contact Lens for Amazon Connect|-|Contact Center AI Insights|
|エンゲージメントのパーソナライズ|Amazon Pinpoint|Notification Hubs|-|
|Eメールの送受信|Amazon Simple Email Service|Azure Communication Services|-|

## Database
||AWS|Azure|GCP|
|---|---|---|---|
|高性能 DB|Amazon Aurora|Azure SQL Database Hyperscale|AlloyDB for PostgreSQL|
|MySQL|Amazon RDS for MySQL|Azure Database for MySQL|Cloud SQL for MySQL|
|PostgreSQL|Amazon RDS for PostgreSQL|Azure Database for PostgreSQL|Cloud SQL for PostgreSQL|
|Oracle|Amazon RDS for Oracle|-|-|
|SQL Server|Amazon RDS for SQL Server|Azure SQL Database|Cloud SQL for SQL Server|
|MariaDB|Amazon RDS for MariaDB|Azure Database for MariaDB|-|
|NoSQL|Amazon DynamoDB|Azure Cosmos DB|Cloud Datastore/Cloud Bigtable|
|Memcached|Amazon ElastiCache for Memcached|-|Memorystore for Memcached|
|Redis|Amazon ElastiCache for Redis|Azure Cache for Redis|Memorystore for Redis|
|グラフDB|Amazon Neptune|Azure Cosmos DB(API for Gremlin)|-|
|時系列DB|Amazon Timestream|Azure Time Series Insights|-|
|MongoDB|Amazon DocumentDB (with MongoDB compatibility)|Azure Cosmos DB(MongoDB API)|-|
|Cassandra|Amazon Keyspaces (for Apache Cassandra)|Azure Managed Instance for ApacheCassandra|-|
|グローバル分散RDB|-|Azure Cosmos DB for PostgreSQL|Cloud Spanner|
|リアルタイムDB|-|-|Cloud Firestore|

## Developer Tools
||AWS|Azure|GCP|
|---|---|---|---|
|開発プロジェクトの管理|AWS CodeStar|Azure DevOps|-|
|Gitリポジトリ|AWS CodeCommit|Azure Repos|Cloud Source Repositories|
|継続的なビルドとテスト|AWS CodeBuild|Azure Pipelines|Cloud Build|
|継続的なデプロイ|AWS CodeDeploy|Azure Pipelines|Cloud Build/Google Cloud Deploy|
|パイプライン|AWS CodePipeline|Azure Pipelines|Cloud Build/Google Cloud Deploy|
|作業の管理|-|Azure Boards|-|
|パッケージレジストリ|AWS CodeArtifact|Azure Artifacts|Artifact Registry|
|テスト計画の管理|-|Azure Test Plans|-|
|IDE|AWS Cloud9|Visual Studio Codespaces|Cloud Shell Code editor|
|分散トレーシング|AWS X-Ray|Azure Application Insights|Cloud Trace|
|ブラウザベースのシェル|AWS CloudShell|Azure Cloud Shell|Cloud Shell|
|カオスエンジニアリング|AWS Fault Injection Simulator|Azure Chaos Studio|-|
|統合ソフトウェア開発サービス|AWS CodeCatalyst|-|-|

## End User Computing
||AWS|Azure|GCP|
|---|---|---|---|
|デスクトップ|Amazon WorkSpaces|Azure Virtual Desktop|-|
|アプリケーションストリーミング|Amazon AppStream 2.0|-|-|
|ストレージ|Amazon WorkDocs|(Office 365)|Google Workspace|
|社内アプリケーションへのモバイルアクセス|Amazon WorkLink|Azure AD Application Proxy|Cloud Identity-Aware Proxy|

## Front-End Web & Mobile
||AWS|Azure|GCP|
|---|---|---|---|
|モバイル/Webアプリケーションの構築とデプロイ|AWS Amplify|Azure Static Web Apps/Azure Mobile Apps|(Firebase)|
|アプリケーションテスト|AWS Device Farm|(Visual Studio App Center)|(Firebase Test Lab)|
|GraphQL|AWS AppSync|-|-|

## Game Tech
||AWS|Azure|GCP|
|---|---|---|---|
|ゲームサーバーホスティング|Amazon GameLift|Azure PlayFab|Google Cloud Game Servers|
|ゲームエンジン|Amazon Lumberyard|-|-|

## Internet of Things
||AWS|Azure|GCP|
|---|---|---|---|
|デバイスとクラウドの接続|AWS IoT Core|Azure IoT Hub|Cloud IoT Core|
|エッジへの展開|AWS Greengrass|Azure IoT Edge|Cloud IoT Edge|
|デバイスから任意の関数を実行|AWS IoT 1-Click|-|-|
|デバイスの分析|AWS IoT Analytics|Azure Stream Analytics/Azure Time Series Insights|-|
|デバイスのセキュリティ管理|AWS IoT Device Defender|-|-|
|デバイスの管理|AWS IoT Device Management|Azure IoT Hub|Cloud IoT Core|
|デバイスで発生するイベントの検出|AWS IoT Events|-|-|
|産業機器からデータを収集|AWS IoT SiteWise|-|-|
|IoTアプリケーションの構築|AWS IoT Things Graph|Azure Digital Twins|-|
|デジタルツイン|AWS IoT TwinMaker|Azure Digital Twins|-|
|位置情報|Amazon Location Service|Azure Maps|Google Maps Platform|
|エッジに配置可能なDB|-|Azure SQL Edge|-|
|車両データの収集|AWS IoT FleetWise|-|-|
|ロボットフリート管理アプリケーションの構築|AWS IoT RoboRunner|-|-|

## Machine Learning
||AWS|Azure|GCP|
|---|---|---|---|
|機械学習モデルの構築|Amazon SageMaker|Azure Machine Learning|Vertex AI|
|ML予測のレビューに必要なワークフローを構築|Amazon Augmented AI|-|-|
|自動コードレビュー|Amazon CodeGuru|-|-|
|自然言語処理|Amazon Comprehend|Text Analytics|Natural Language AI|
|不正検出|Amazon Fraud Detector|-|-|
|ヘルスデータの保存と分析|Amazon HealthLake|Azure API for FHIR|Cloud Healthcare API|
|エンタープライズ検索|Amazon Kendra|Azure Cognitive Search|-|
|チャットボットの構築|Amazon Lex|Azure Bot Service|Dialogflow|
|Text-to-Speech|Amazon Polly|Speech Services|Text-to-Speech|
|画像認識|Amazon Rekognition|Computer Vision|Vision AI|
|翻訳|Amazon Translate|Translator Text|Translation AI|
|Speech-to-Text|Amazon Transcribe|Speech Services|Speech-to-Text|
|レコメンデーション|Amazon Personalize|Personalizer|Recommendations AI|
|時系列予測|Amazon Forecast|-|-|
|ドキュメント検出|Amazon Textract|Azure Form Recognizer|Document AI|
|推論の高速化|Amazon Elastic Inference|-|Cloud TPU|
|データセットの構築|Amazon SageMaker Ground Truth|Azure Machine Learning data labeling|Vertex Data Labeling|
|ノートブック|Amazon SageMaker Studio Notebooks|Azure Machine Learning|Vertex AI Workbench|
|MLデータの準備|Amazon SageMaker Data Wrangler|-|-|
|ビジョンモデルのカスタマイズ|Amazon Rekognition Custom Labels|Custom Vision|Vertex AI|
|音声モデルのカスタマイズ|-|Custom Speech|-|
|言語処理モデルのカスタマイズ|Amazon Comprehend|-|Vertex AI|
|翻訳モデルのカスタマイズ|Amazon Translate Custom Terminology |Translator Text Custom Translator|Vertex AI |
|MLを活用したクラウド運用|Amazon DevOps Guru|-|-|
|センサーデータ分析による異常動作検出|Amazon Lookout for Equipment|-|-|
|製品欠陥の検出|Amazon Lookout for Vision|-|-|
|時系列データの異常検知|Amazon Lookout for Metrics|Anomaly Detector|-|
|エンドツーエンドの産業機器監視|Amazon Monitron|-|-|
|エッジでのコンピュータービジョン|AWS Panorama|Azure Percept|-|
|Deep Learning用仮想マシンイメージ|AWS Deep Learning AMIs|Data Science Virtual Machines|Deep Learning VM Image|
|Deep Learning用コンテナイメージ|AWS Deep Learning Containers|-|Deep Leaning Containers|
|コーディングコンパニオン|Amazon CodeWhisperer|(GitHub Copilot)|-|
|ゲノムデータ分析|Amazon Omics|-|Cloud Life Sciences|
|生成系 AI|Amazon Bedrock|Azure OpenAI Service|Vertex AI|

## Managemnet & Governance
||AWS|Azure|GCP|
|---|---|---|---|
|モニタリング|Amazon CloudWatch|Azure Monitor|Cloud Monitoring|
|リソースの作成と管理|AWS CloudFormation|Azure Resource Manager|Cloud Deployment Manager|
|アクティビティの追跡|AWS CloudTrail|Azure Activity Log|Cloud Audit Logs|
|リソースの設定変更の記録、監査|AWS Config|-|Cloud Asset Inventory|
|構成管理サービスの展開|AWS OpsWorks(Chef/Puppet)|-|-|
|ITサービスカタログの管理|AWS Service Catalog|Azure Managed Applications|Private Catalog|
|インフラストラクチャの可視化と制御|AWS Systems Manager|Azure Automanage|VM Manager|
|パフォーマンスとセキュリティの最適化|AWS Trusted Advisor|Azure Advisor|Recommender|
|使用しているサービスの状態表示|AWS Personal Health Dashboard|Azure Resource Health|-|
|基準に準拠したアカウントのセットアップ|AWS Control Tower|Azure Blueprints|Policy Intelligence|
|ライセンスの管理|AWS License Manager|-|-|
|クラウドプロバイダによるインフラの運用管理|AWS Managed Services|-|-|
|ワークロードの見直しと改善|AWS Well-Architected Tool|-|-|
|複数アカウントの管理|AWS Organizations|Azure Management Group|Resource Manager|
|プライベートSSH/RDP接続|AWS Systems Manager Session Manager|Azure Bastion|Cloud Identity-Aware Proxy|
|ChatOps|AWS Chatbot|-|-|
|パラメーターストア|AWS Systems Manager Parameter Store|App Configuration|-|
|リソースの移動|-|Azure Resource Mover|-|
|VM 管理の簡素化|-|Azure Automanage|-|
|コンテナ/サーバーレスデプロイメントの管理|Amazon Proton|Azure Deployment Environments|-|
|Grafana|Amazon Managed Service for Grafana|Azure Managed Grafana|-|
|Prometheus|Amazon Managed Service for Prometheus|Azure Monitor managed service for Prometheus|Google Cloud Managed Service for Prometheus|
|アプリケーションの回復力を定義、検証、追跡|AWS Resilience Hub|-|-|

## Media Services
||AWS|Azure|GCP|
|---|---|---|---|
|メディア変換|Amazon Elastic Transcoder/AWS Elemental MediaConvert|Azure Media Services - Encoding|Transcoder API|
|ライブ動画処理|AWS Elemental MediaLive|Live and On-demand Streaming|Livestream API|
|ライブストリーミング配信|Amazon Interactive Video Service|-|-|
|動画の配信とパッケージング|AWS Elemental MediaPackage|Azure Media Services|(Anvato)|
|動画ファイル向けストレージ|AWS Elemental MediaStore|-|-|
|ターゲティング広告の挿入|AWS Elemental MediaTailor|-|Video Stitcher API|
|デジタルコンテンツ作成スタジオ|Amazon Nimble Studio|-|-|

## Migration & Transfer
||AWS|Azure|GCP|
|---|---|---|---|
|移行の管理|AWS Migration Hub|-|-|
|移行のアセスメント|AWS Application Discovery Service|Azure Migrate|-|
|データベースの移行|AWS Database Migration Service|Azure Database Migration Service|Database Migration Service|
|オンプレミスからのデータ転送|AWS DataSync|Azure File Sync|-|
|サーバーの移行|AWS Application Migration Service/AWS Server Migration Service|Azure Migrate|Migrate for Compute Engine|
|ディザスタリカバリ|AWS Elastic Disaster Recovery |Azure Site Recovery|-|
|大容量データの移行|Snowファミリー|Azure Data box|Transfer Appliance|
|SFTP|AWS Transfer for SFTP|-|-|
|クラウド間のデータ転送|-|-|Cloud Storage Transfer Service|
|メインフレームのモダナイゼーション|AWS Mainframe Modernization|-|-|

## Networking & Content Delivery
||AWS|Azure|GCP|
|---|---|---|---|
|仮想ネットワーク|Amazon Virtual Private Cloud|Azure Virtual Network|Virtual Private Cloud|
|APIの管理|Amazon API Gateway|API Apps/API Management|API Gateway/Cloud Endpoints/Apigee|
|CDN|Amazon CloudFront|Azure CDN|Cloud CDN|
|DNS|Amazon Route 53|Azure DNS|Cloud DNS/Domains|
|プライベート接続|Amazon VPC PrivateLink|Azure Private Link|Private Access Options for Services|
|サービスメッシュ|AWS App Mesh|Azure Service Fabric Mesh|Traffic Director|
|サービスディスカバリー|AWS Cloud Map|-|Service Directory|
|専用線接続|AWS Direct Connect|Azure ExpressRoute|Cloud Interconnect|
|DNSベース負荷分散|Amazon Route 53|Azure Traffic Manager|Cloud DNS|
|グローバルエンドポイント|AWS Global Accelerator|Azure Front Door|Cloud Load Balancing|
|ハブ&スポーク型ネットワーク接続|AWS Transit Gateway|Azure Virtual Network Manager|-|
|ネットワークパフォーマンスの監視|AWS Transit Gateway Network Manager|Network Watcher|Network Intelligence Center|
|グローバルワイドエリアネットワークの構築|AWS Cloud WAN|Azure Virtual WAN|Network Connectivity Center|
|プライベート 5Gの構築|AWS Private 5G|Azure Private 5G Core |-|
|VPNなしの企業アプリケーションへのアクセス|AWS Verified Access|Azure AD Application Proxy|Cloud Identity-Aware Proxy|


## Quantum Technologies
||AWS|Azure|GCP|
|---|---|---|---|
|量子コンピューティング|Amazon Braket|Azure Quantum|-|

## Robotics
||AWS|Azure|GCP|
|---|---|---|---|
|ロボット工学|AWS RoboMaker|-|-|

## Satellite
||AWS|Azure|GCP|
|---|---|---|---|
|人工衛星の地上局|AWS Ground Station|Azure Orbital|-|

## Security, Identity & Compliance
||AWS|Azure|GCP|
|---|---|---|---|
|ID管理|AWS Identity and Access Management|Azure Active Directory|Cloud IAM| 
|階層型データストア|Amazon Cloud Directory|-|-|
|セキュリティデータの分析、視覚化|Amazon Detective|-|-|
|アプリケーションのID管理|Amazon Cognito|Azure Active Directory B2C|Identity Platform|
|脅威検出|Amazon GuardDuty|Azure Advanced Threat Protection|Security Command Center|
|サーバーのセキュリティの評価|Amazon Inspector|Microsoft Defender for Cloud|Security Command Center|
|機密データの検出と保護|Amazon Macie|Azure Information Protection|Cloud Data Loss Prevention|
|コンプライアンスレポートへのアクセス|AWS Artifact|(Service Trust Portal)|Compliance Reports Manager|
|SSL/TLS証明書の管理|AWS Certificate Manager|App Service Certificates|Certificate Manager|
|プライベートCA|AWS Certificate Manager Private Certificate Authority|-|Certificate Authority Service|
|ハードウェアセキュリティモジュール |AWS Cloud HSM|Azure Dedicated HSM|Cloud HSM|
|Active Directory|AWS Directory Service|Azure Active Directory Domain Services|Managed Service for Microsoft Active Directory|
|ファイアウォールルールの一元管理|AWS Firewall Manager|Azure Firewall Manager|-|
|キーの作成と管理|AWS Key Management Service|Azure Key Vault|Cloud Key Management Service|
|機密情報の管理|AWS Secrets Manager|Azure Key Vault|Secret Manager|
|セキュリティ情報の一括管理|AWS Security Hub|Azure Sentinel|Security Command Center|
|DDoS保護|AWS Shield|Azure DDoS Protection|Cloud Armor|
|シングルサインオン|AWS IAM Identity Center|Azure Active Directory B2C|Cloud Identity|
|WAF|AWS WAF|Azure Application Gateway|Cloud Armor|
|仮想ネットワークファイアウォール|AWS Netowrk Firewall|Azure Firewall|-|
|使用状況の継続的な監査|AWS Audit Manager|-|
|IDS|-|Azure Firewall|Cloud IDS|
|セキュリティログの集約・管理|Amazon Security Lake|-|-|
|アプリケーションのアクセス権限と認可の管理|Amazon Verified Permissions|-|-|
|決済用 HSM|AWS Payment Cryptography|Azure Payment HSM|-|

## Serverless
||AWS|Azure|GCP|
|---|---|---|---|
|サーバーレスアプリケーションの構築|AWS Application Composer|-|-|

## Storage
||AWS|Azure|GCP|
|---|---|---|---|
|オブジェクトストレージ|Amazon S3|Azure Blob|Cloud Storage|
|ブロックストレージ|Amazon EBS|Managed Disk|Persistent Disk|
|ファイルストレージ(NFS)|Amazon Elastic File System|Azure Files|Cloud Filestore|
|ファイルストレージ(SMB)|Amazon FSx for Windows File Server|Azure Files|-|
|NetApp ONTAP|Amazon FSx for NetApp ONTAP|Azure NetApp Files|-|
|HPC向けファイルシステム|Amazon FSx for Lustre|Azure Managed Lustre|-|
|NetApp ONTAP|Amazon FSx for NetApp ONTAP|Azure NetApp Files|-|
|OpenZFS|Amazon FSx for OpenZFS|-|-|
|アーカイブストレージ|Amazon S3 Glacier|Storage archive access tier|Cloud Storage Coldline|
|バックアップの一元管理|AWS Backup|Azure Backup|Backup and DR Service|
|ハイブリットストレージ|AWS Storage Gateway|Azure StorSimple|-|
|ディザスタリカバリ|AWS Elastic Disaster Recovery|Azure Site Recovery|Backup and DR Service|

## 参考情報
### AWS Products
https://aws.amazon.com/jp/products/

### Azure Products
https://azure.microsoft.com/ja-jp/services/

### GCP Products
https://cloud.google.com/products/

### AWS to Azure services comparison
https://docs.microsoft.com/ja-jp/azure/architecture/aws-professional/services

### AWS サービスや Azure サービスと Google Cloud を比較する
https://cloud.google.com/docs/get-started/aws-azure-gcp-service-comparison


----------------------------------------------------------------------------

## web
資格
- [【全22種 AI資格掲載中】国内外のAI資格を徹底調査しました](https://www.codexa.net/ai_certification/)
- [今注目のAI関連資格「G検定」とは？合格者が勉強法を徹底解説！](https://www.codexa.net/jdla-generalist-test/)
- [AIエンジニアを目指す人は必見！E資格合格までの道のり【ディープランニング】](https://rightcode.co.jp/blog/information-technology/ai-engineer-jdla-deep-learning-for-engineer)

データセット
- [【24個掲載】機械学習で使えるデータセット一挙勢揃い！](https://www.codexa.net/ml-dataset-list/)

知識  
- [機械学習エンジニアのリアルな実態調査 – 仕事内容や年収から、必須のスキル・経験まで！](https://www.codexa.net/machine_learning_engineer/)
- [R言語とは？機械学習エンジニアが知っておくべきR言語の概要やPythonとの比較まとめ](https://www.codexa.net/what-is-r/)
- [機械学習エンジニアってどんな人？人工知能開発チームに属する人材の肩書き](https://www.codexa.net/ai-team-job-titles/)
- [人間と区別がつかないAIチャットボット？](https://www.codexa.net/smartest-ai-chatbot/)
- [第3世代のニューラルネットワーク「Spiking Neural Networks」とは？](https://rightcode.co.jp/blog/information-technology/spiking-neural-networks)
- [人工知能の欠点、破局的忘却とは？](https://rightcode.co.jp/blog/information-technology/machine-learning-catastrophic-forgetting)
- [教師なし機械学習「VAE」による連続的な手書き文字の生成](https://rightcode.co.jp/blog/information-technology/unsupervised-learning-vae-continuous-handwriting-generation)

会社の機械学習ブログ  
- [RIGHTCODE 機械学習特集](https://rightcode.co.jp/blog/feature/machine-learning-blog-list)

機械学習ブログ
- [Daniel Bourke](https://www.mrdbourke.com/)
- [統計学の時間](https://bellcurve.jp/statistics/course/)
- [渋谷駅前で働くデータサイエンティストのブログ](https://tjo.hatenablog.com)
- [からっぽのしょこ](https://www.anarchive-beta.com/about)
- [楽しみながら理解するAI・機械学習入門](https://data-analytics.fun)
- [米国データサイエンティスト](https://datawokagaku.com)
- [トタデータブログ](https://totadata.com)
- [G検定用語集](https://zero2one.jp/ai-word/)

機械学習のためのYoutube  
- [予備校のノリで学ぶ「大学の数学・物理」](https://www.youtube.com/c/yobinori)
- [キノコード/プログラミング学習チャンネル](https://www.youtube.com/c/kinocode)
- [Alcia Solid Project](https://www.youtube.com/channel/UC2lJYodMaAfFeFQrGUwhlaQ)

機械学習関係のニュース  
- [AI-SCHOLAR: 最新AI論文をキャッチアップ](https://ai-scholar.tech/)
- [IT media](https://www.itmedia.co.jp/keywords/machine_learning.html)
- [IT media 戦略人事の時代](https://www.itmedia.co.jp/business/subtop/jinji/)
- [AI（人工知能）関連メディア](https://ledge.ai)
- [Data Artist : AI × 活用術](https://www.data-artist.com/contents/ai-applications.html)
- [Data Artist : AI × ニュース](https://www.data-artist.com/contents/ai-news.html)
- [towards data science](https://towardsdatascience.com)

## 書籍
数学  
- [Pythonで理解する微分積分の基礎](https://www.amazon.co.jp/-/en/%E4%BA%95%E5%8F%A3-%E5%92%8C%E4%B9%8B/dp/4297127792/ref=sr_1_4?crid=2GDOCLS310S4R&keywords=python+%E3%81%A7%E7%90%86%E8%A7%A3%E3%81%99%E3%82%8B&qid=1665626983&qu=eyJxc2MiOiIwLjAwIiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=python%E3%81%A7%E7%90%86%E8%A7%A3%E3%81%99%E3%82%8B%2Caps%2C295&sr=8-4)
- [最短コースでわかる　ディープラーニングの数学](https://www.amazon.co.jp/%E6%9C%80%E7%9F%AD%E3%82%B3%E3%83%BC%E3%82%B9%E3%81%A7%E3%82%8F%E3%81%8B%E3%82%8B-%E3%83%87%E3%82%A3%E3%83%BC%E3%83%97%E3%83%A9%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0%E3%81%AE%E6%95%B0%E5%AD%A6-%E8%B5%A4%E7%9F%B3-%E9%9B%85%E5%85%B8/dp/4296102508)
- [人工知能プログラミングのための数学がわかる本](https://www.amazon.co.jp/-/en/%E7%9F%B3%E5%B7%9D-%E8%81%A1%E5%BD%A6/dp/4046021969/ref=sr_1_1?crid=1Z24YFRK6ETBD&keywords=%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E6%95%B0%E5%AD%A6&qid=1663058317&s=books&sprefix=%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E6%95%B0%E5%AD%A6%2Cstripbooks%2C250&sr=1-1)
- [1冊でマスター　大学の微分積分](https://www.amazon.co.jp/gp/product/477416545X/ref=as_li_qf_asin_il_tl?ie=UTF8&tag=yobinori-22&creative=1211&linkCode=as2&creativeASIN=477416545X&linkId=bbcae55d91a083454f7df219407ab878)
- [1冊でマスター　大学の線形代数](https://www.amazon.co.jp/-/en/%E7%9F%B3%E4%BA%95-%E4%BF%8A%E5%85%A8/dp/4774170372/ref=pd_bxgy_img_sccl_1/357-0025936-8639765?pd_rd_w=13ySf&content-id=amzn1.sym.918446e7-72f4-48c7-a672-af3b6ace2b19&pf_rd_p=918446e7-72f4-48c7-a672-af3b6ace2b19&pf_rd_r=PZQTTXXQVJ3Z01SFK3HJ&pd_rd_wg=ngN2t&pd_rd_r=ac48342b-f8d5-4a4c-a2d0-3d6653d9669c&pd_rd_i=4774170372&psc=1)

統計学  
- [漫画でわかる統計学　素朴な疑問からゆるーく解説](https://www.amazon.co.jp/-/en/%E5%A4%A7%E4%B8%8A-%E4%B8%88%E5%BD%A6/dp/479734251X/ref=sr_1_1?adgrpid=54805103953&gclid=CjwKCAjwsMGYBhAEEiwAGUXJaRDNQe6Qk1Y8IYch53TeajYd6i47o6LcoLxTlP4BBzLwA29Zg7y4mRoC42gQAvD_BwE&hvadid=618680891936&hvdev=c&hvlocphy=1009343&hvnetw=g&hvqmt=e&hvrand=6886431017290821897&hvtargid=kwd-332756291693&hydadcr=27703_14598626&jp-ad-ap=0&keywords=%E6%BC%AB%E7%94%BB%E3%81%A7%E3%82%8F%E3%81%8B%E3%82%8B%E7%B5%B1%E8%A8%88%E5%AD%A6&qid=1662077551&sr=8-1)
- [Pythonで理解する統計解析の基礎](https://www.amazon.co.jp/%E8%B0%B7%E5%90%88-%E5%BB%A3%E7%B4%80/dp/4297100495/ref=sr_1_1_sspa?crid=2GDOCLS310S4R&keywords=python+%E3%81%A7%E7%90%86%E8%A7%A3%E3%81%99%E3%82%8B&qid=1665626983&qu=eyJxc2MiOiIwLjAwIiwicXNhIjoiMC4wMCIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=python%E3%81%A7%E7%90%86%E8%A7%A3%E3%81%99%E3%82%8B%2Caps%2C295&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE3R0oxU1RRNU5TUFomZW5jcnlwdGVkSWQ9QTAyMDI4NDJHMkFRU0gwUzY5WUYmZW5jcnlwdGVkQWRJZD1BMldLSldVT0xZMVRDRCZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=)
- [統計学入門（基礎統計学I）](https://www.amazon.co.jp/-/en/%E6%9D%B1%E4%BA%AC%E5%A4%A7%E5%AD%A6%E6%95%99%E9%A4%8A%E5%AD%A6%E9%83%A8%E7%B5%B1%E8%A8%88%E5%AD%A6%E6%95%99%E5%AE%A4/dp/4130420658/ref=sr_1_7?crid=2ZH1MAI9EUF09&keywords=%E7%B5%B1%E8%A8%88%E5%AD%A6&qid=1662077601&sprefix=%E7%B5%B1%E8%A8%88%E5%AD%A6%2Caps%2C161&sr=8-7)
- [改訂版　日本統計学会公式認定　統計検定2級対応　統計学基礎](https://www.amazon.co.jp/-/en/%E7%94%B0%E4%B8%AD%E8%B1%8A/dp/4489022271/ref=pd_bxgy_img_sccl_1/357-0025936-8639765?pd_rd_w=mU0lu&content-id=amzn1.sym.918446e7-72f4-48c7-a672-af3b6ace2b19&pf_rd_p=918446e7-72f4-48c7-a672-af3b6ace2b19&pf_rd_r=X3HPG3P22G4A618AK3X9&pd_rd_wg=Issa2&pd_rd_r=ac38e513-a52d-4efd-9d74-1fae09319541&pd_rd_i=4489022271&psc=1)

前処理  
- [前処理大全[データ分析のためのSQL/R/Python実践テクニック]](https://www.amazon.co.jp/-/en/%E6%9C%AC%E6%A9%8B-%E6%99%BA%E5%85%89-ebook/dp/B07C3JFK3V/ref=sr_1_1?crid=ADDQ1KRBT4KV&keywords=%E5%89%8D%E5%87%A6%E7%90%86%E5%A4%A7%E5%85%A8&qid=1662104390&s=books&sprefix=%E5%89%8D%E5%87%A6%E7%90%86%E5%A4%A7%E5%85%A8%2Cstripbooks%2C317&sr=1-1)
- [Pandasデータ前処理入門](https://www.amazon.co.jp/-/en/%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE%E3%83%AD%E3%83%B3%E3%83%90%E3%83%BC%E3%83%88-ebook/dp/B084MD5DGG/ref=sr_1_1?keywords=%E5%89%8D%E5%87%A6%E7%90%86Pandas%E3%83%87%E3%83%BC%E3%82%BF%E5%89%8D%E5%87%A6%E7%90%86%E5%85%A5%E9%96%80&qid=1662104447&s=books&sr=1-1)

機械学習  
- [機械学習のエッセンス　実装しながら学ぶPython、数学、アルゴリズム](https://www.amazon.co.jp/-/en/%E5%8A%A0%E8%97%A4-%E5%85%AC%E4%B8%80-ebook/dp/B07GYS3RG7/ref=sr_1_1?crid=WH1PLDQ0SGKS&keywords=%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%81%AE%E3%82%A8%E3%83%83%E3%82%BB%E3%83%B3%E3%82%B9&qid=1663070036&sprefix=%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%2Caps%2C197&sr=8-1)
- [[第3版]Python機械学習プログラミング　達人データサイエンティストによる理論と実践](https://www.amazon.co.jp/dp/B08LYWFPQ9/ref=sspa_dk_detail_6?psc=1p13NParams&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyRE5HNjlOSU04RlEwJmVuY3J5cHRlZElkPUEwNDUzNzQ5RUtDWURLRlNEVFBCJmVuY3J5cHRlZEFkSWQ9QVFZSFRaVlJLNkZLNiZ3aWRnZXROYW1lPXNwX2RldGFpbCZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=)
- [scikit-learn, Keras, Tensorflowによる実践機械学習　第2版](https://www.amazon.co.jp/-/en/Aur%C3%A9lien-G%C3%A9ron/dp/4873119286/ref=sr_1_1?crid=38C0UX5D7GXU0&keywords=scikit-learn+keras+tensorflow%E3%81%AB%E3%82%88%E3%82%8B%E5%AE%9F%E8%B7%B5%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92&qid=1663112672&s=books&sprefix=scikit+%2Cstripbooks%2C225&sr=1-1)
- [Kaggleで勝つデータ分析の技術](https://www.amazon.co.jp/%E9%96%80%E8%84%87-%E5%A4%A7%E8%BC%94/dp/4297108437/ref=d_pd_vtp_sccl_2_8/357-0025936-8639765?pd_rd_w=8Mcyb&content-id=amzn1.sym.cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_p=cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_r=0E8SEPDK10PG44VECMD5&pd_rd_wg=wSj7A&pd_rd_r=0e50728a-f89b-4c11-a2e2-64d4e9943fff&pd_rd_i=4297108437&psc=1)

深層学習  
- [ゼロから作るDeep Learning -Pythonで学ぶディープラーニングの理論と実装](https://www.amazon.co.jp/-/en/%E6%96%8E%E8%97%A4-%E5%BA%B7%E6%AF%85/dp/4873117585/ref=d_pd_vtp_sccl_2_3/357-0025936-8639765?pd_rd_w=39X1J&content-id=amzn1.sym.cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_p=cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_r=NYB97PCVYTXCQD2F9K91&pd_rd_wg=2hQI8&pd_rd_r=cbb4197a-d8ce-4208-8ce2-96978fdd36ea&pd_rd_i=4873117585&psc=1)
- [ゼロから作るDeep Learning➋ -自然言語処理編](https://www.amazon.co.jp/-/en/%E6%96%8E%E8%97%A4-%E5%BA%B7%E6%AF%85/dp/4873118360/ref=pd_bxgy_img_sccl_1/357-0025936-8639765?pd_rd_w=IpAS7&content-id=amzn1.sym.918446e7-72f4-48c7-a672-af3b6ace2b19&pf_rd_p=918446e7-72f4-48c7-a672-af3b6ace2b19&pf_rd_r=GVMAAVM35KE3S9TTC7GJ&pd_rd_wg=Bqlg4&pd_rd_r=c1ad48e5-e171-4144-8a5d-6f12d840c9cd&pd_rd_i=4873118360&psc=1)

データ分析者のための書籍シリーズ
- [分析者のためのデータ解釈学入門](https://www.amazon.co.jp/-/en/%E6%B1%9F%E5%B4%8E%E8%B2%B4%E8%A3%95/dp/4802612907/ref=d_pd_vtp_sccl_2_3/357-0025936-8639765?pd_rd_w=8Mcyb&content-id=amzn1.sym.cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_p=cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_r=0E8SEPDK10PG44VECMD5&pd_rd_wg=wSj7A&pd_rd_r=0e50728a-f89b-4c11-a2e2-64d4e9943fff&pd_rd_i=4802612907&psc=1)
- [データ分析のための数理モデル入門](https://www.amazon.co.jp/-/en/%E6%B1%9F%E5%B4%8E-%E8%B2%B4%E8%A3%95/dp/4802612494/ref=pd_lpo_1?pd_rd_w=X5n15&content-id=amzn1.sym.d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_p=d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_r=93ZMB8R2VEKCHT2HH50G&pd_rd_wg=RJxCn&pd_rd_r=615a4b2a-113e-4d04-9de3-fda443c9ddc1&pd_rd_i=4802612494&psc=1)
- [データ分析に必須の知識・考え方　統計学入門](https://www.amazon.co.jp/-/en/%E9%98%BF%E9%83%A8-%E7%9C%9F%E4%BA%BA/dp/4802613199/ref=pd_lpo_2?pd_rd_w=X5n15&content-id=amzn1.sym.d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_p=d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_r=93ZMB8R2VEKCHT2HH50G&pd_rd_wg=RJxCn&pd_rd_r=615a4b2a-113e-4d04-9de3-fda443c9ddc1&pd_rd_i=4802613199&psc=1)
- [本質を捉えたデータ分析のための分析モデル入門](https://www.amazon.co.jp/-/en/%E6%9D%89%E5%B1%B1%E8%81%A1/dp/4802613776/ref=pd_lpo_3?pd_rd_w=X5n15&content-id=amzn1.sym.d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_p=d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_r=93ZMB8R2VEKCHT2HH50G&pd_rd_wg=RJxCn&pd_rd_r=615a4b2a-113e-4d04-9de3-fda443c9ddc1&pd_rd_i=4802613776&psc=1)

100本ノック  
- [Python実践データ分析100本ノック　第2版](https://www.amazon.co.jp/dp/B0B3LQHK1L/ref=sspa_dk_detail_0?psc=1p13NParams&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzRVlPVzcxRFBPMUQ2JmVuY3J5cHRlZElkPUEwODMzOTI5MVhBVzY1OTVPNFNHOSZlbmNyeXB0ZWRBZElkPUEzR1o1WFNLWEgyNUlYJndpZGdldE5hbWU9c3BfZGV0YWlsJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
- [Python実践データ加工/可視化100本ノック](https://www.amazon.co.jp/dp/B09B8PB4FG/ref=sspa_dk_detail_0?psc=1p13NParams&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEySlBDUURLTzgwM0FHJmVuY3J5cHRlZElkPUEwNjU0NjI1MlRZT0g3MVZNUERGSCZlbmNyeXB0ZWRBZElkPUExNDIwUzRGNFk2NDNIJndpZGdldE5hbWU9c3BfZGV0YWlsJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
- [Python実践AIモデル構築 100本ノック](https://www.amazon.co.jp/-/en/%E4%B8%8B%E5%B1%B1%E8%BC%9D%E6%98%8C-ebook/dp/B09G2K5VJ9/ref=sr_1_4?crid=T4NC0BV2MMC4&keywords=100%E6%9C%AC%E3%83%8E%E3%83%83%E3%82%AF&qid=1662105014&s=books&sprefix=100%2Cstripbooks%2C191&sr=1-4)
- [Python実践機械学習システム100本ノック](https://www.amazon.co.jp/-/en/%E4%B8%8B%E5%B1%B1-%E8%BC%9D%E6%98%8C/dp/479806341X/ref=pd_lpo_3?pd_rd_w=BIV4W&content-id=amzn1.sym.d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_p=d769922e-188a-40cc-a180-3315f856e8d6&pf_rd_r=7XJVPY9YHX20G7MBT80B&pd_rd_wg=fawhW&pd_rd_r=f34df23c-5072-4024-bda2-079e98d33169&pd_rd_i=479806341X&psc=1)

知識系
- [人工知能は人間を超えるか　ディープラーニングの先にあるもの](https://www.amazon.co.jp/-/en/%E6%9D%BE%E5%B0%BE-%E8%B1%8A/dp/4040800206/ref=sr_1_1?crid=1MZW22NEEFNVM&keywords=%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD%E3%81%AF%E4%BA%BA%E9%96%93%E3%82%92%E8%B6%85%E3%81%99%E3%82%8B%E3%81%8B&qid=1663112491&sprefix=%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD%E3%81%AF%2Caps%2C248&sr=8-1)
- [深層学習教科書　ディープラーニング　G検定（ジェネラリスト）公式テキスト　第2版](https://www.amazon.co.jp/-/en/%E7%8C%AA%E7%8B%A9-%E5%AE%87%E5%8F%B8/dp/4798165948/ref=d_pd_vtp_sccl_3_1/357-0025936-8639765?pd_rd_w=f0xnb&content-id=amzn1.sym.cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_p=cbb45385-7b99-44b7-a528-bff5ddaa153d&pf_rd_r=Z4YXDAN82AXYD20F66BP&pd_rd_wg=jK16M&pd_rd_r=f7543d04-bde6-48ea-abc2-177cbf9165bb&pd_rd_i=4798165948&psc=1)

## Udemy
https://www.udemy.com/user/seiji-28/

機械学習  
- [Machine Learning A-Z™: Hands-On Python & R In Data Science](https://www.udemy.com/course/machinelearning/)
- [【前編】米国データサイエンティストがやさしく教える機械学習超入門【Pythonで実践】](https://www.udemy.com/course/mlpython-1/)
- [【後編】米国データサイエンティストがやさしく教える機械学習超入門【Pythonで実践】](https://www.udemy.com/course/mlpython-2/)

統計学
- [統計検定2級対策講座](https://www.udemy.com/course/toukei-kentei/)
- [一番理解できる統計学ベーシック講座その1【確率分布・推定・検定】](https://www.udemy.com/course/statistics_basic/)
- [一番理解できる統計学ベーシック講座その2【相関分析・回帰分析】](https://www.udemy.com/course/statistics_basic_vol2/)

Tensorflow
- [TensorFlow Developer Certificate in 2022: Zero to Mastery](https://www.udemy.com/course/tensorflow-developer-certificate-machine-learning-zero-to-mastery/)

PyTorch
- [PyTorch for Deep Learning in 2023: Zero to Mastery](https://www.udemy.com/course/pytorch-for-deep-learning/)

## coursera
機械学習
- [機械学習専門講座](https://www.coursera.org/specializations/machine-learning-introduction#courses)

## 資格
機械学習関係の資格

|No.|資格名|
|:---:|:---:|
| 01 | [E資格](https://www.jdla.org/certificate/engineer/)  
| 02 | [G検定](https://www.jdla.org/certificate/general/)  
| 03 | [データサイエンティスト検定リテラシーレベル](https://www.datascientist.or.jp/dskentei/)  
| 04 | [AI実装検定S級](https://kentei.ai/)  
| 05 | [AI実装検定A級](https://kentei.ai/)  
| 06 | [統計検定2級](https://www.toukei-kentei.jp/exam/grade2/)  
| 07 | [統計検定準1級](https://www.toukei-kentei.jp/exam/grade1semi/)  
| 08 | [統計検定1級](https://www.toukei-kentei.jp/exam/grade1/)  
| 09 | [数学検定1級](https://www.su-gaku.net/suken/examination/summary/1q/)  
| 10 | [Python3エンジニア認定データ分析試験](https://www.pythonic-exam.com/exam/analyist)  
| 11 | [Google Cloud Associate Cloud Engineer](https://cloud.google.com/certification/cloud-engineer)  
| 12 | [Google Cloud Professional Cloud Architect](https://cloud.google.com/certification/cloud-architect)  
| 13 | [Google Cloud Professional Data Engineer](https://cloud.google.com/certification/data-engineer?hl=ja)  
| 14 | [Google Cloud Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)  
| 15 | [Google Cloud Professional Cloud Network Engineer](https://cloud.google.com/certification/cloud-network-engineer)  
| 16 | [Google Cloud Professional Cloud DevOps Engineer](https://cloud.google.com/certification/cloud-devops-engineer)  
| 17 | [Google Cloud Professional Cloud Developer](https://cloud.google.com/certification/cloud-developer)  
| 18 | [Google Cloud Professional Machine Learning Engineer](https://cloud.google.com/certification/machine-learning-engineer?hl=ja)  
| 19 | [TensorFlow Developer Certification](https://www.tensorflow.org/certificate)  
