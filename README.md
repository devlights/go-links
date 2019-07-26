# Go言語関連記事のリンク集

後で見るとマークしている情報へのリンク集です。（順不同）

---

- [基本](#basics)
- [github](#github)
- [情報が沢山あるサイト](#many_golang_articles)
- [golang](#golang)
- [gcp](#gcp)
- [Goならわかるシステムプログラミング](#go_system_programming)

---

## basics

- [Go Official Page](https://golang.org/)
- [Go Documentation](https://golang.org/doc/)
- [Go Effective Go](https://golang.org/doc/effective_go.html)
- [Go FAQ](https://golang.org/doc/faq)
- [Go Tour of Go](https://tour.golang.org/welcome/1)
- [Go Packages](https://golang.org/pkg/)
- [Go Playground](https://play.golang.org/)
- [Go Wiki](https://github.com/golang/go/wiki)

## github

- [yaegi](https://github.com/containous/yaegi)
- [vecty](https://github.com/gopherjs/vecty)
- [bokchoy](https://github.com/thoas/bokchoy)
  - Redisをバックエンドに利用しているシンプルなジョブキューライブラリ
- [go-echarts](https://github.com/chenjiandongx/go-echarts)
  - チャートライブラリ。高機能。
- [project-layout](https://github.com/golang-standards/project-layout)
  - Go言語のプロジェクト構成についての資料
- [excelize](https://github.com/360EntSecGroup-Skylar/excelize)
  - Excelを操作できるライブラリ。```xlsx``` と比べて多機能
  - セル指定が ```A1``` 形式なのですこし使いづらい印象
- [xlsx](https://github.com/tealeg/xlsx)
  - Excelを読み書きできるライブラリ。シートコピーなどは出来ない
  - セルの指定が ```sheet.Rows[y].Cells[x].Value``` と出来るので使いやすい
- [tablewriter](https://github.com/olekukonko/tablewriter)
- [gin](https://github.com/gin-gonic/gin)
  - 軽量 Web フレームワーク
  - ハイパフォーマンス (内部で httprouter を利用している)
- [httprouter](https://github.com/julienschmidt/httprouter)
  - ハイパフォーマンス http リクエストルーター
- [golang-set](https://github.com/deckarep/golang-set)
  - set の 実装
- [goquery](https://github.com/PuerkitoBio/goquery)
  - jqueryライクにHTMLを操作できるライブラリ
- [awesome-go](https://github.com/avelino/awesome-go)
- [deque(Extremely fast ring-buffer deque)](https://github.com/gammazero/deque)
- [gore](https://github.com/motemen/gore)
  - Yet another Go REPL
  - Go言語用のREPL
- [tint](https://github.com/printzero/tint)
  - ターミナルの出力に色をつけてくれるライブラリ

## many_golang_articles

- [Attempting to Learn Go](https://github.com/shindakun/atlg)
- [AN INTRODUCTION TO PROGRAMMING IN GO](http://www.golang-book.com/books/intro?ref=cybrhome)
- [Algorithms to Go](https://yourbasic.org/)
- [golangprograms](http://www.golangprograms.com/)
- [Qiita - Goタグ](https://qiita.com/tags/go)
- [Go Language Patterns](http://www.golangpatterns.info/)
- [Go Bootcamp](http://www.golangbootcamp.com/book/frontmatter)
- [逆引きGolang](https://ashitani.jp/golangtips/index.html)
- [Learn Go with tests](https://quii.gitbook.io/learn-go-with-tests/)
- [Go by Example](https://gobyexample.com/)
- [Go Language Tutorials](https://www.cybrhome.com/topic/go-language-tutorials)
- [Go Tutorial](https://www.tutorialspoint.com/go)

## golang

- [Go言語でCSVファイルにレコードを追加する](https://qiita.com/uji_/items/ab4b358461dfb09e705d)
- [Timeout a Function Call (with Goroutines & Channels)](https://golangcode.com/timing-out-a-goroutine/)
- [Go言語でエクセルデータから情報を読み取る](https://qiita.com/ikeponsu/items/34a8ded9a6306c3b6468)
- [Using Service Objects in Go](https://itnext.io/using-service-objects-in-go-d899dc599335)
- [Go: Buffered and Unbuffered Channels](https://medium.com/@blanchon.vincent/go-buffered-and-unbuffered-channels-29a107c00268)
- [Writing delightful HTTP middleware in Go](https://doordash.engineering/2019/07/22/writing-delightful-http-middlewares-in-go/)
- [How to handle paths for supporting files in a package in Go?](https://forum.golangbridge.org/t/how-to-handle-paths-for-supporting-files-in-a-package-in-go/14651)
- [5 reasons to use Golang](https://dev.to/carloslfu/5-reasons-to-use-golang-3d3h)
- [Go Slices are Fat Pointers](https://nullprogram.com/blog/2019/06/30/)
- [Go: Improve the Usage of Your Goroutines with GODEBUG](https://medium.com/@blanchon.vincent/go-improve-the-usage-of-your-goroutines-with-godebug-4d1f33970c33)
- [Clear is better than clever](https://dave.cheney.net/2019/07/09/clear-is-better-than-clever)
- [Introduction to Concurrency in Go: Gopher Farm](https://medium.com/@olena_stoliarova/introduction-to-concurrency-in-go-gopher-farm-3aa23f253420)
- [Process synchronization monitors in go](https://medium.com/@angadsharma1016/process-synchronization-monitors-in-go-d31f4c42fce7)
- [Bitmap indexes in Go: unbelievable search speed](https://badootech.badoo.com/bitmap-indexes-in-go-unbelievable-search-speed-bb4a6b00851)
- [The anatomy of Slices in Go](https://medium.com/rungo/the-anatomy-of-slices-in-go-6450e3bb2b94)
- [Writing a Chat Server in Go](https://medium.com/@nqbao/writing-a-chat-server-in-go-3b61ccc2a8ed)
- [Go Pointers: Why I Use Interfaces (in Go)](https://medium.com/@kent.rancourt/go-pointers-why-i-use-interfaces-in-go-338ae0bdc9e4)
- [Go’s wrapped return pattern to clean up objects with background goroutines](https://medium.com/@cep21/gos-wrapped-return-pattern-to-clean-up-objects-with-background-goroutines-b3454846a0d)
- [How to use the io.Writer interface](https://yourbasic.org/golang/io-writer-interface-explained/)
- [【Golang】io.Writer インタフェース](https://qiita.com/mztnnrt/items/2425fa2a70572c088f4a)
- [【Golang】io.Readerインタフェース](https://qiita.com/mztnnrt/items/ddf6920a484e74f0ee1a)
- [GoでHTTPサーバを立てる](https://qiita.com/kkyouhei/items/8ce72bf997fa353b7646)
- [【golang】Unixドメインソケット通信](https://qiita.com/mztnnrt/items/009ad99387457ebe112d)
- [【golang】UDPソケット通信](https://qiita.com/mztnnrt/items/406952f200fa956ebe1d)
- [【Golang】TCPソケット通信](https://qiita.com/mztnnrt/items/3c02e2f0d5562a80a28f)
- [Golangでのstreamの扱い方を学ぶ](https://christina04.hatenablog.com/entry/2017/01/06/190000)
- [Goにはディレクトリ構成のスタンダードがあるらしい](https://qiita.com/sueken/items/87093e5941bfbc09bea8)
  - 大事なのは、```cmd``` ディレクトリ. この下にアプリケーションの名前のディレクトリを作り、その下に ```main.go``` を配置
- [Golangのスケジューラあたりの話](https://qiita.com/takc923/items/de68671ea889d8df6904)
- [DockerでGoの開発環境を構築する](https://qiita.com/uji_/items/8c9eda89526abe0ba900)
- [Language Design in the Service of Software Engineering](https://talks.golang.org/2012/splash.article)
- [6年間におけるGoのベストプラクティス](https://postd.cc/go-best-practices-2016/)
- [私のプログラミングの始め方 : Go](https://yakst.com/ja/posts/831)
- [Go入門②~package/importについて・簡単なtestコードを書いてみる~](https://qiita.com/shuuuting95/items/aedfff75e2083688c579)
- [Go言語 termdash のBarChart（棒グラフ）の使い方（CPU使用率表示）](https://qiita.com/h6591/items/b9f3282dc5f41f6150c2)
- [Go言語 コンソールモードでコンソール上にグラフ、ボタン、スクロールテキストを表示するtermdashの紹介](https://qiita.com/h6591/items/2964ec7c8d8e53d5ac0a)
- [Pipes 101 with Go](http://www.albertoleal.me/posts/golang-pipes.html)
- [Golangの良いところ](https://christina04.hatenablog.com/entry/why-golang-is-good)
- [Non-Blocking I/O, I/O Multiplexing, Asynchronous I/Oの区別](https://christina04.hatenablog.com/entry/2017/07/05/005944)
- [イベントループなしでのハイパフォーマンス – C10K問題へのGoの回答](https://postd.cc/performance-without-the-event-loop/)

## gcp

- [Go言語で開発したWebアプリをGCP(GKE)へデプロイして公開する](https://qiita.com/melty_go/items/6ec8b1e423dc1d63da24)
- [Go言語で開発したWebアプリをGCP(GAE)へデプロイする](https://qiita.com/melty_go/items/074af694aa8a1c8ec798)
- [【GCP入門編・第1回】エンジニア必読！今さら聞けない、Google Cloud Platform (GCP) とは？](https://www.topgate.co.jp/gcp01-what-is-google-cloud-platform)
- [【GCP入門編・第2回】まずは、ここから！知らないと恥ずかしい Google Cloud Platform (GCP) の事前準備！](https://www.topgate.co.jp/gcp02-getting-started-guide)
- [【GCP入門編・第3回】難しくない！ Google Compute Engine (GCE) でのインスタンス起動方法！](https://www.topgate.co.jp/gcp03-google-compute-engine-launch-instance)
- [【GCP入門編・第4回】すぐ出来なくても大丈夫！サンプルアプリで Google Compute Engine (GCE) の動作練習！](https://www.topgate.co.jp/gcp04-google-compute-engine-run-application)
- [【GCP入門編・第5回】 Google App Engine の魅力とは？ Google App Engine (GAE) でのアプリケーション起動方法！](https://www.topgate.co.jp/gcp05-google-app-engine-run-application)
- [【GCP入門編・第6回】これは簡単！ Google App Engine での Cloud Datastore の利用方法！](https://www.topgate.co.jp/gcp06-how-to-use-cloud-datastore-gae)
- [【GCP入門編・第7回】知らなきゃ損！ Google Container Engine (GKE) での Dockerイメージを使ったコンテナの起動方法！](https://www.topgate.co.jp/gcp07-how-to-start-docker-image-gke)
- [【GCP入門編・第8回】 Container Registry での Docker イメージの使用方法！](https://www.topgate.co.jp/gcp08-how-to-use-docker-image-container-registry)
- [【GCP入門編・第9回】 Cloud Shell で、いつでもどこでも Google Cloud Platform (GCP) が操作可能に！](https://www.topgate.co.jp/gcp09-how-to-use-cloud-shell)
- [【GCP入門編・第10回】スケーラブルな NoSQL データベースサービス Cloud Bigtable を使ってみよう！](https://www.topgate.co.jp/gcp10-how-to-use-cloud-bigtable)
- [【GCP入門編・第11回】 Google Cloud Dataproc を使ってデータを解析しよう！](https://www.topgate.co.jp/gcp11-analyze-data-using-google-cloud-dataproc)
- [【GCP入門編・第12回】 BigQuery を使って気軽にビッグデータの解析を行ってみよう！](https://www.topgate.co.jp/gcp12-how-to-analyze-big-data-with-bigquery)
- [【GCP入門編・第13回】 Cloud Datalab でデータの可視化を行ってみよう！](https://www.topgate.co.jp/gcp13-visualize-data-with-cloud-datalab)
- [【GCP入門編・第14回】 Cloud Functions を使ってサーバレスアーキテクチャを体験しよう！](https://www.topgate.co.jp/gcp14-using-serverless-architecture-by-cloud-functions)
- [【GCP入門編・第15回】 GCP から AWS までモニタリングできる Google Stackdriver を紹介！](https://www.topgate.co.jp/gcp15-what-is-google-stackdriver)
- [【GCP入門編・第16回】アプリのパフォーマンスを視覚的に確認できる Stackdriver Monitoring を紹介！](https://www.topgate.co.jp/gcp16-what-is-stackdriver-monitoring)
- [【GCP入門編・第17回】 Stackdriver Monitoring で Google Compute Engine を監視しよう！](https://www.topgate.co.jp/gcp17-stackdriver-monitoring-gce)
- [【GCP入門編・第18回】 Stackdriver Monitoring で Google App Engine の監視をしよう！](https://www.topgate.co.jp/gcp18-stackdriver-monitoring-gae)
- [【GCP入門編・第19回】 Stackdriver Monitoring でメールや Slack による通知を設定しよう！](https://www.topgate.co.jp/gcp19-stackdriver-monitoring-notify-mail-slack)
- [【GCP入門編・第20回】 手間いらずでログ管理ができる Stackdriver Logging のご紹介！](https://www.topgate.co.jp/gcp20-what-is-stackdriver-logging)
- [【GCP入門編・第21回】 Stackdriver Logging でアプリケーションのログを収集しよう！](https://www.topgate.co.jp/gcp21-stackdriver-logging-collect-application-logs)
- [【GCP入門編・第22回】 Stackdriver Logging で収集したログに対して、フィルタの実行や警告を設定しよう！](https://www.topgate.co.jp/gcp22-stackdriver-logging-setting-logs)
- [【GCP入門編・第23回】 Stackdriver Error Reporting でアプリケーションのエラーを収集しよう！](https://www.topgate.co.jp/gcp23-stackdriver-error-reporting)
- [【GCP入門編・第24回】 Stackdriver Debugger で本番環境のデバッグを行おう！](https://www.topgate.co.jp/gcp24-stackdriver-debugger)
- [【GCP入門編・第25回】 Cloud SQL for MySQL で Master-Slave 構成を組もう！](https://www.topgate.co.jp/gcp25-cloud-sql-for-mysql-master-slave)
- [【GCP入門編・第26回】 Cloud DNS でドメインの DNS レコードを作成しよう！](https://www.topgate.co.jp/gcp26-domain-operation-by-cloud-dns)
- [【GCP入門編・第27回】インスタンステンプレートを使って、よく使うインスタンスを素早く立ち上げよう！](https://www.topgate.co.jp/gcp27-instance-template-gce)
- [【GCP入門編・第28回】インスタンスグループを使って複数のインスタンスを管理する](https://www.topgate.co.jp/gcp28-instance-groups)
- [【GCP入門編・第29回】Cloud Load Balancing で Web アプリケーションにロードバランサーを設定する](https://www.topgate.co.jp/gcp29-cloud-load-balancing)
- [【GCP入門編・第30回】 Cloud CDNで静的ファイルの配布を行う](https://www.topgate.co.jp/gcp30-cloud-cdn)
- [【GCP入門編・第31回】 GCP のネットワークにサブネットを追加する](https://www.topgate.co.jp/gcp31-gcp-subnet)

## go_system_programming

- [Goで覗くシステムプログラミングの世界](https://ascii.jp/elem/000/001/234/1234843/)
- [低レベルアクセスへの入り口（1）：io.Writer](https://ascii.jp/elem/000/001/243/1243667/)
- [低レベルアクセスへの入り口（2）：io.Reader前編](https://ascii.jp/elem/000/001/252/1252961/)
- [低レベルアクセスへの入り口（3）：io.Reader後編](https://ascii.jp/elem/000/001/260/1260449/)
- [Goから見たシステムコール](https://ascii.jp/elem/000/001/267/1267477/)
- [GoでたたくTCPソケット（前編）](https://ascii.jp/elem/000/001/276/1276572/)
- [GoでたたくTCPソケット（後編）](https://ascii.jp/elem/000/001/403/1403717/)
- [UDPソケットをGoで叩く](https://ascii.jp/elem/000/001/411/1411547/)
- [Unixドメインソケット](https://ascii.jp/elem/000/001/415/1415088/)
- [ファイルシステムと、その上のGo言語の関数たち（1）](https://ascii.jp/elem/000/001/423/1423022/)
- [ファイルシステムと、その上のGo言語の関数たち（2）](https://ascii.jp/elem/000/001/430/1430904/)
- [ファイルシステムと、その上のGo言語の関数たち（3）](https://ascii.jp/elem/000/001/440/1440099/)
- [Go言語で知るプロセス（1）](https://ascii.jp/elem/000/001/451/1451470/)
- [Go言語で知るプロセス（2）](https://ascii.jp/elem/000/001/459/1459279/)
- [Go言語で知るプロセス（3）](https://ascii.jp/elem/000/001/467/1467705/)
- [Go言語と並列処理](https://ascii.jp/elem/000/001/475/1475360/)
- [Go言語と並列処理（2）](https://ascii.jp/elem/000/001/480/1480872/)
- [Go言語と並列処理（3）](https://ascii.jp/elem/000/001/486/1486902/)
- [Go言語のメモリ管理](https://ascii.jp/elem/000/001/496/1496211/)
- [Go言語とコンテナ](https://ascii.jp/elem/000/001/502/1502967/)
