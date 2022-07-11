# aadakouda
**Webアプリケーションのバックエンド開発経験があり、ソフトウェアエンジニア職を志望しています！**

## 基本情報
- SIer勤務、開発部署所属3年目。
- 明治大学 政治経済学部 経済学科 卒。
- AtCoder 茶色：[https://atcoder.jp/users/kouda](https://atcoder.jp/users/kouda)
- LinkedIn：[https://www.linkedin.com/in/miyumiya/](https://www.linkedin.com/in/miyumiya/)
- はてなブログ：[https://kame3xkame3.hatenablog.jp](https://kame3xkame3.hatenablog.jp)

## 経緯・動機
もともとはIT営業やコンサルタントのようなキャリアを目指して現職を志望しました。

入社当初はIT分野の知識に疎く悩んでいたところ、開発職→営業職のようなキャリアパスがあると知り、開発部署へ配属を希望しました。

しかし、新卒研修で覚えたプログラミングが非常に楽しかったため、このまま技術職でキャリアを継続したいと思うようになりました。

現職でも開発に携わっていますが、コーディングや設計など技術的な業務に注力したいこと、より大規模で社会的なインパクトのあるシステムに関わりたいと思い、ソフトウェアエンジニア職を志望しています。

## スキル
- Java ★★★★☆
- Python ★★★★☆
- SQL ★★★★☆
- Backend ★★★★☆
- Frontend ★★★☆☆
- HTML/CSS ★★★☆☆
- Git ★★★☆☆
- JavaScript ★★☆☆☆
- React.js ★★☆☆☆
- Docker ★★☆☆☆
- Algorithms & Data Structures ★★☆☆☆

## 言語
- 日本語 ★★★★★
- 英語 ★★★★☆
- 大学時代にフランス・リヨン政治学院への3ヶ月の留学経験があります。
- 外国語学習が好きで、大学時代に英語・フランス語・スペイン語・ドイツ語・ロシア語・アラビア語・古典ギリシャ語・ラテン語の単位を取得しました。

## 資格
入社当初は何を勉強して良いか分からず、体系的な学習とモチベーション維持のために資格をたくさん利用しました。

- **応用情報技術者・基本情報技術者**
	- [IPA 独立行政法人 情報処理推進機構：制度の概要：応用情報技術者試験](https://www.jitec.ipa.go.jp/1_11seido/ap.html)
	- 文系かつ未経験でIT業界に入ったため、情報系の知識を補うために受験しました。
	- 午後問題は低レイヤーに関する知識の欠如・ソフトウェアエンジニアのキャリアを意識して選択しました。
		- 基本情報技術者の選択問題：ソフトウェア・ハードウェア、ソフトウェア設計、データ構造及びアルゴリズム、アセンブラ
		- 応用情報技術者の選択問題：プログラミング、ネットワーク、データベース、組込みシステム開発
- **Oracle Certified Java Programmer, Gold SE 11・Silver SE 8**
	- [Java SE 11 Programmer II (1Z0-816-JPN) 試験 | Oracle University](https://www.oracle.com/jp/education/certification/1z0-816-jpn-31705-ja.html)
	- 業務でのスキルアップのために受験しました。
	- 業務都合で古いバージョンを使用しているため、キャッチアップ目的でGold受験時はより新しいバージョンで受験しました。
- **LinuC Level2**
	- [LinuCレベル2 Version 10.0 試験概要 | Linux技術者認定試験 リナック | LPI-Japan](https://linuc.org/linuc2/)
	- 業務であまりLinuxやCLIを使用しないため、CLI操作に憧れて受験しました。
	- Dockerやインフラ知識、プロセスなどについても触れることができて、とても良い経験になりました。
- **HTML5 プロフェッショナル認定試験 Level1**
	- [HTML5プロフェッショナル認定試験 レベル1について（Ver2.5）｜試験概要｜Web資格なら「HTML5プロフェッショナル認定試験」公式サイト](https://html5exam.jp/outline/lv1.html)
	- 体系的にHTML/CSSを勉強したいと思い受験しました。
- **OSS-DB Silver**
	- [OSS-DB Silver](https://oss-db.jp/outline/silver)
	- SELECT/INSERT/UPDATE/DELETEを覚えた頃に受かるだろうと思って受験しました。
	- DDL、DML、DCLやPostgreSQLの設定ファイルなど試験範囲内でも知らないことがたくさんあったので、開発業務で使っている技術以外にも目を向けるきっかけになりました。
- **TOEIC 855**

## 制作物
- **[aadakouda/file_maker](https://github.com/aadakouda/file_maker)**
	- 業務時間短縮のために作成したツールです。
	- 業務都合で多くのテストケースを手動で実施し、スクリーンショットとExcelで結果を残す必要があったため、Pythonで自動化する処理をたくさん書きました。
	- 業務時間で作成したものがあるためコードは一部しか載せられませんが、他にも下記のようなものなどを作成しました。
		- .logファイルに出力されている特定のAPIのレスポンスJSONを抽出し、各キーの値が想定したものと一致しているかチェックして結果を出力する。
		- 正常なテストケースの入力値を大量に作成する。
		- テスト結果資料のためのフォルダとその中身の複数のファイルを連番で作成する。
		- テスト実施後に出力される複数の.csvファイルの帳票から、特定のユーザーIDのレコードを抽出し、帳票ごとにデータの表やテスト結果をExcelに整形して出力する。
	- テスト結果の資料作成に1日１～２時間かかっていたのが、**数秒で作成**できるようになりました。
	- Excelの書式が統一され、**誰でも早く綺麗な資料作成**ができるようになりました。
	- 機械的にチェックしているため、**テスト結果の確認ミスがなくなりました**。
- **[aadakouda/mercari-build-training-2022](https://github.com/aadakouda/mercari-build-training-2022)**
	- [Build@Mercari](https://mercan.mercari.com/articles/33259/)に参加した際の課題です。
	- バックエンドの言語にはPythonを使用しました。
	- 他にもGit/GitHub、Docker、docker-compose、TypeScript、React.js、API開発を経験しました。
- **[aadakouda/Hackathon4BuildAtMercari](https://github.com/aadakouda/Hackathon4BuildAtMercari)**
	- 前述のBuild@Mercariのハッカソンでチーム開発しました。
	- 「メルカリの出品機能」をテーマに、物々交換で出品・購入できる機能を発表しました。
	- アイディア発案とMock・バックエンド開発を担当しました。
- **[aadakouda/aho3](https://github.com/aadakouda/aho3)**
	- 世界のナベアツを再現するネタアプリです。
	- 自分でAWSにアプリをデプロイしてみたくて作成しました。
	- AWS EC2、Nginx、Systemdを自分で設定してデプロイしました。
	- 業務ではJSPでWebページを作っていたので、フロントエンドとバックエンドを分けて開発してみました。
- **[aadakouda/calendar](https://github.com/aadakouda/calendar)**
	- Neumorphismなデザインのカレンダーアプリです。
	- JavaScriptの練習のためと、偶然見つけたCSSデザインを自分でも実装してみたくて作成しました。
- **[aadakouda/competitiveProgramming](https://github.com/aadakouda/competitiveProgramming)**
	- 競技プログラミング等で解いた問題の解答コードを載せています。
