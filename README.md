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

### [クックパッド株式会社](https://info.cookpad.com/)

- [Ruby の会社でなぜ Rust？　 Cookpad がマイナー言語を採用するまで](https://logmi.jp/282807)

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

### [株式会社Handii](https://www.handii.co.jp/)

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
- クラウドAPIサービス[mimi®](https://fairydevices.jp/mimi)のバックエンドの一部でRustを利用しています。
- クライアントサイドのライブラリやSDKでもRustを活用していく予定です。
- 求人情報は[こちら](https://www.green-japan.com/company/4267)。

### [株式会社アークエッジ・スペース](https://arkedgespace.com/)

- 人工衛星のフライトソフトウェア
- その他、各種ソフトウェア

### [株式会社PEZY Computing](https://www.pezy.co.jp)

- スーパーコンピュータ向けのプロセッサLSIを作っている会社です。
- プロセッサLSIの設計支援にRustを活用しています。
    - プロセッサ検証用の命令セットシミュレータやコンポーネントの検証モデル
    - プロセッサのソースコードやドキュメント、テストケースの自動生成
    - LSI設計言語(SystemVerilog)の[linter](https://github.com/dalance/svlint)及び[Language Server](https://github.com/dalance/svls)

### [株式会社 POL](https://pol.co.jp/)

- LabTech（研究 × Technology）領域で事業を展開している会社です。
- 3 つのサービスを運営しています。
  - 理系学生と企業を結ぶ採用マッチングプラットフォーム [LabBase](https://labbase.jp/)
  - 理系特化のオンラインイベントプラットフォーム [LabBase Now](https://now.compass.labbase.jp/)
  - 研究開発者・技術者に特化した転職/採用サービス [LabBase plus](https://plus.labbase.jp/)
- プラットフォーム基盤開発に Rust を採用し、開発を進めています。

### [フルカイテン株式会社](https://corp.full-kaiten.com/)

- 小売業の在庫の運用効率を上げ、売上・粗利・キャッシュフローを最大化する在庫分析のSaaSサービスを開発しています。
- 予測、集計システムの結果を可視化するためのGraphqlや、Lambdaから起動するバッチ処理にRustを使用しています。
