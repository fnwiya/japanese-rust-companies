# 日本で Rust を利用している会社一覧

(inspired by [日本で Erlang/OTP や Elixir を利用している会社一覧](https://github.com/voluntas/japanese-erlang-elixir-companies) / [日本で Clojure/ClojureScript を利用している会社一覧](https://github.com/athos/japanese-clojure-companies))

- 日本国内版
- 追加したい会社がある場合はプルリクエストを送ってください
  - 後ろに付け足していってください
  - コミットログは英語でも日本語でも大丈夫です
- 求人情報歓迎

こうした方が良いなどありましたら Twitter で [@fnwiya](https://twitter.com/fnwiya) か GitHub Issue へお気軽にご連絡ください。

## テンプレート

```
### [会社名](会社 URL)

- 箇条書きで rust のプロダクション利用について好きなだけ

会社のアピールや求人を好きなだけ
```

## 会社一覧

### [フォルシア株式会社](https://www.forcia.com/)

- [Shinjuku.rs](https://forcia.connpass.com/event/105485/)を主催しています

### [ピクシブ株式会社](https://www.pixiv.co.jp/)

### [Idein Inc.](https://idein.jp/)

- IoT プラットホームの [Actcast](https://actcast.io) で使っている
  - アプリケーションサーバ
  - Raspberry Pi 上で動くエージェント

### [クックパッド株式会社](https://cookpad.jobs/)

- SRE チームを中心にパフォーマンスや堅牢さが求められるシーンで利用しています。
- 例:
  - プッシュ通知配信基盤 ([Ruby の会社でなぜ Rust？　 Cookpad がマイナー言語を採用するまで](https://logmi.jp/282807))
  - https://github.com/cookpad/ecamo

### [株式会社ＦＦＲＩ](https://www.ffri.jp/)

### [Axelspace Corp.](https://www.axelspace.com/)

- 人工衛星からのデータ（テレメトリ）の解析に使っています。

### [株式会社ユーザベース](https://www.uzabase.com/)

- 企業・業界情報プラットフォーム[SPEEDA](https://jp.ub-speeda.com/)のデータ分析に使っています。
- 大量データを高速に登録するために使っています。

### [株式会社サイバーエージェント](https://www.cyberagent.co.jp/)

- アドベリフィケーション事業の配信サーバに使っています。
- Rust で最速 WebFramework をつくるゼミをやっています。

### [株式会社オプティム](https://www.optim.co.jp/)

- [https://tech-blog.optim.co.jp/entry/2019/01/07/173000#usage-in-optim](https://tech-blog.optim.co.jp/entry/2019/01/07/173000#usage-in-optim)

### [株式会社ドワンゴ](http://dwango.co.jp/)

- [https://dwango.github.io/articles/frugalos/](https://dwango.github.io/articles/frugalos/)

### [一般社団法人 tonari](https://tonari.no)

- 離れた空間をつなぐ次世代コミュニケーションプラットフォーム
- ネットワーキング、圧縮、画像処理など、全コードベースを Rust で開発しています。

### [株式会社Mobility Technologies](https://mo-t.com/)

- ドライブレコーダーで動作するDeep LearningやComputer Visionを含むシステムの開発言語として採用しています
- [エッジMLシステムをC/C++からRustへ移行した事例](https://docs.google.com/presentation/d/1HOL9jheJnKkh2q7w3hU_px-je1qL7lxrSXV-0P1hces/)

### [株式会社ペイルド](https://www.paild.co.jp/)

- Handiiの運営する法人向けウォレットサービス[paild](https://www.paild.io/)のサーバーサイドの開発言語として利用しています。
- Webframeworkはactix-webを利用中。

### [キャディ株式会社](https://corp.caddi.jp/recruit/eng)

- 会社について
    - 金属加工品の受発注プラットフォーム [CADDi](https://caddi.jp/) を運営しています。
    - エンジニアチームは、キャディのオペレーションチームや、顧客、サプライパートナーの利用するシステムを作って事業を支えています。
- Rust の利用について
    - https://caddi.tech/archives/2331
    - 複数の業務システムのバックエンド開発を Rust で行っています
    - 二次元図面の画像解析アルゴリズム開発でも採用しています
    - Rust を用いた WebAssembly と WebGL を組み合わせて、図面ビューアを開発しています

### [フェアリーデバイセズ株式会社](https://fairydevices.jp/)

- 音声技術をコアにしてデバイスやサービスを作っている会社です。
- 主に以下でRustを使用しています。
  - 現場DXを支える自社開発デバイス[THINKLET](https://mimi.fairydevices.jp/technology/device/thinklet/)を中心とした複数のクラウドシステムのバックエンドおよびフロントエンド
  - クラウドAPIサービス[mimi®](https://mimi.fairydevices.jp/)のバックエンド
  - クライアントサイドのライブラリやSDKでもRustを活用していく予定です

### [株式会社アークエッジ・スペース](https://arkedgespace.com/)

- 人工衛星のフライトソフトウェア
- その他、各種ソフトウェア

### [株式会社PEZY Computing](https://www.pezy.co.jp)

- スーパーコンピュータ向けのプロセッサLSIを作っている会社です。
- プロセッサLSIの設計支援にRustを活用しています。
    - プロセッサ検証用の命令セットシミュレータやコンポーネントの検証モデル
    - プロセッサのソースコードやドキュメント、テストケースの自動生成
    - LSI設計言語(SystemVerilog)の[linter](https://github.com/dalance/svlint)及び[Language Server](https://github.com/dalance/svls)

### [株式会社 LabBase ](https://labbase.co.jp/)
#### 会社情報
- LabTech（研究 × Technology）領域で事業を展開している会社です。
- 3 つのサービスを運営しています。
  - 理系学生と企業を結ぶ採用マッチングプラットフォーム [LabBase](https://compass.labbase.jp/)
  - 理系特化のオンラインイベントプラットフォーム [LabBase Now](https://now.compass.labbase.jp/)
  - 研究開発者・技術者に特化した転職/採用サービス [LabBase plus](https://plus.labbase.jp/)
- 上記三つのサービスとプラットフォーム基盤開発に Rust を採用し、開発を進めています。
#### 求人情報
- 開発情報
  - サーバーサイド：Rust、Axum
  - フロントエンド: TypeScript、React
  - DB/インフラ　: MySQL、Amazon DynamoDB、AWS、Cloudflare
- 給与	600〜1100万円
- フルリモート
- [求人詳細はこちら](https://herp.careers/v1/polinc/requisition-groups/d7b2cf5c-8551-42b7-a907-6a6d173c7c36)

### [フルカイテン株式会社](https://corp.full-kaiten.com/)

- 小売業の在庫の運用効率を上げ、売上・粗利・キャッシュフローを最大化する在庫分析のSaaSサービスを開発しています。
- 予測、集計システムの結果を可視化するためのGraphqlや、Lambdaから起動するバッチ処理にRustを使用しています。

### [株式会社フィードフォース](https://www.feedforce.jp/)

- [Omni Hub](https://apps.shopify.com/omni-hub) という Shopify アプリを Rust で開発しています
- actix-web、diesel、juniper などのライブラリを利用しています

### [株式会社クロスビット](https://x-bit.co.jp)

- 「らくしふ」の自動シフトスケジューリング機能(組合せ最適化)でRustを使っています
- [Xbit Entrance book](https://www.notion.so/xbit/Xbit-Entrance-book-115f8879d36d42b2ae544fbf2fb4eb85)
- [週末なにしてますか? 競プロで忙しいですか? 弊社で現実のスケジューリング問題を解いてもらっていいですか?｜株式会社クロスビット](https://note.com/xbit_recruit/n/ncaf991bc033f)

### [株式会社 estie](https://www.estie.jp/corp/)

- 弊社はオフィス不動産市場のDXを目指す不動産テック企業で[オフィス探しのestie](https://www.estie.jp/)や[オフィス情報プラットフォームestie pro](https://leasing.estiepro.jp/)を提供しています。
- 新規プロダクトで Rust を使っています: [estie、Rustで新プロダクト作るってよ - 2022/2/16](https://speakerdeck.com/estie/16)
- [estie エンジニア採用情報](https://jobs.estie.jp/) にて詳細な採用情報を公開しています。
  - 「不動産テックってなにやってるの？」という気軽な気持ちでカジュアル面談に申し込んでいただけたら幸いです。

### [ユニークビジョン株式会社](https://www.uniquevision.co.jp/)

- SNSマーケティングツール「Belugaシリーズ」を開発しています
  - [Beluga](https://beluga.uniquevision.co.jp/) : Twitter/Facebook/Instagramのアカウントを一元管理できるツールとして、企業のSNS運用をサポートします
  - [Beluga キャンペーン](https://bc.uniquevision.co.jp/) : Twitter自動返信やインスタントウィンキャンペーンを提供。スピーディで品質の高いキャンペーンを実現します
  - [Beluga チャットボット](https://bcb.uniquevision.co.jp/) : TwitterのDM機能を用いたチャットボットの構築が可能。ユーザーと自動でメッセージの往復を行えます
- 複数サービスの開発に、様々な用途で Rust を採用しています
  - 複数のシステムのバックエンド（フレームワークにはActix Webを使用）
  - クローラなどの常駐プログラム
  - メモリ使用量を抑えたい処理など部分的に採用するケースもあります


### [株式会社KICONIA WORKS](https://kiconiaworks.com)

KICONIA WORKSはAIモデル開発やシステム開発を通じて顧客課題を解決する、様々な業界で活躍してきたAIエンジニア/データサイエンティストによる少数精鋭のチームです。

以下のような分野でRustを利用しています。

- 建設業界向けの自動設計システムのアルゴリズム・バックエンドのすべてをRustで開発しています。
- 建設業界向けの自動設計システムUIの一部をRustで高速化しています。
- スマートフォン向けのアプリ開発でRustで開発した自社ライブラリとFlutterを利用することでマルチプラットフォームへの対応を行っています。

### [GMOペパボ株式会社](https://pepabo.com/)

- オリジナルアイテム・グッズを手軽に作成・販売できる「[SUZURI](https://suzuri.jp)」というサービスで、画像変換サーバーに Rust を採用しています。
  - [SUZURI 技術スタック](https://tech.pepabo.com/tech-stack/suzuri/)

### [Finatext Holdings Ltd.](https://hd.finatext.com/)

プラットフォームチームにてコンポーネントやツールをRustで開発しています。OSSとして公開しているもの:

- https://github.com/Finatext/orgu
  - [ブログ記事](https://techblog.finatext.com/orgu-e3a3ad0219a8)
- https://github.com/Finatext/gls
  - [登壇資料](https://speakerdeck.com/taiki45/efficient-platform-for-security-and-compliance-89d1ad22-14d6-44df-ab7e-dc4ca7fb470c)

採用情報:

- [エンジニア向け採用資料](https://speakerdeck.com/finatext/finatext-are-hiring-engineers)

興味がある方は気軽にカジュアル面談など申し込んでいただけるとうれしいです！

### [ドクターメイト株式会社](https://doctormate.co.jp/)

- ドクターメイト株式会社はデジタルの力を活用することで、介護の現場から医療に関わるリスクや負担を軽減し、介護従事者が安心して日々のケアに集中できる体制づくりをサポートしています。
- サービスのバックエンドを Rust (axum, async-graphql) で開発しています。
  - [その他技術スタック](https://whatweuse.dev/company/doctor_mate)
- [カジュアル面談](https://herp.careers/v1/doctormate/3l6Guniw02L3)を実施しています。オンラインでお気軽にお話ししませんか？

### [Miletos株式会社](https://miletos.tech/)

- 主にエンタープライズ企業に対して、[経費精算システム](https://sapphire.miletos.tech/)と[入金消し込みシステム](https://stream.miletos.tech/)を自社開発しています。
- Rustの利用箇所
  - 経費精算システムのバックエンド全て
    - actix-web 
    - async-graphql
    - diesel / sqlx 
  - 入金消し込みシステムのバックエンド全て
    - axum
    - async-graphql
    - sqlx
- 求人情報
  - 給与: 600 ~ 1200万以上
  - 募集ポジションは[こちら](https://herp.careers/v1/miletos)
  - [弊社がエンジニアに期待すること](https://miletos.notion.site/c54c6ee7b0de43d8bc8e1eacd9aa91ed)

### [CollaboGate](https://nodecross.io/)

- CollaboGateは、「データインフラをシンプルにし、産業の変革を支える」をミッションに掲げるサイバーセキュリティスタートアップです。分散型ID技術を活用し、世界中のIoT機器とクラウドを安全に繋ぐデジタルトラスト基盤「NodeX（ノード・クロス）」を開発しています。このインフラ技術を軸に、パートナー企業のIoT事業成長を支援する、そんな事業を展開しています。
- サービスのバックエンド全般でRust を採用しています。
- [採用情報](https://collabogate.notion.site/CollaboGate-9de87dfb448b4c3fa02af707c6c3d855)


### [NOWIST株式会社](https://nowist.co.jp/)
- [介護求人セレクト](https://www.kaigojobselect.com/)のバックエンドAPIでRustを採用しています。


### [FRAIM株式会社](https://fraim.co.jp/)

- 契約書の作成・検索・レビューを効率化する業務効率化サービス[LAWGUE](https://lawgue.com/)を自社開発しています。
- 主にBackendで以下のようなcrateを用いて開発を行っています
  - axum
  - async-graphql
- また、文書解析やbrowserでwasmを実行するケースにも利用しております

### [Jij Inc.](https://www.j-ij.com/ja)

- 会社について
  - 業務内容：量子・古典ハイブリッド技術を活用した数理最適化ソリューションの開発・提供
  - 採用情報: https://www.j-ij.com/ja/recruit
- Rustの利用について
  - 数理最適化ソフトウェア群をRustとPythonで開発しています。特にコアとなるPythonパッケージを[PyO3](https://github.com/PyO3/pyo3)で開発しています。
  - OSSになっているもの
    - [OMMX](https://github.com/Jij-Inc/ommx)
    - [pyo3-stub-gen](https://github.com/Jij-Inc/pyo3-stub-gen)
    - [serde-pyobject](https://github.com/Jij-Inc/serde-pyobject)
  - ブログ記事
    - [Jijのプロダクト開発にRustを採用した](https://zenn.dev/jij_inc/articles/fa5693fa2c7e27)
    - [Haskeller の異常な愛情：または、生粋の Haskeller は転職して Rust を一ヶ月半書いて何を思うようになったか](https://zenn.dev/jij_inc/articles/2024-12-18-pure-haskeller-writing-rust)
  - [Rust.Tokyo 2024 Silver Sponsor](https://rust.tokyo/sponsors)

### [アミフィアブル株式会社](https://www.amifiable.co.jp/recruit)

アミフィアブル株式会社は、AI技術を活用してソフトウェア開発の効率化と品質向上を実現する先進的な企業です。Rustを中心とした最先端技術でテスト自動化の革新に挑戦し、Rustエンジニアの成長に適した環境を提供しています。

#### 技術スタック

- バックエンド: Rust（Actix Webフレームワーク）
- フロントエンド: React + TypeScript
- デスクトップアプリ: Electron（Tauriへの移行を進めてます）

### [株式会社PocketChange](https://about.pocket-change.jp/)

- 電子マネー作成サービスを作ったり、外貨両替の端末を作って提供しています。
- 主に2つのサービスを運営しています。
  - 誰でも自社のオリジナル電子マネーを作成できるサービス [Pokepay](https://pokepay.jp/)
  - 外貨のコインや紙幣を電子マネーに交換できる端末 [PocketChange](https://pocket-change.jp/)
- [Pokepay](https://pokepay.jp/) のバックエンド開発、チャージ機のハードウェア(RaspberryPi)、ファームウェアなどで Rust を採用しています。
- 技術スタック
   - バックエンド: axum, async-graphql など
   - フロントエンド: Flutter, Reactなど
- [採用情報はこちら](https://about.pocket-change.jp/careers/backend-engineer-rust-en)
