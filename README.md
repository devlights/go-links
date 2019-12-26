# Go言語関連記事のリンク集

後で見るとマークしている情報へのリンク集です。（順不同）

---

- [基本](#basics)
- [github](#github)
- [TUI](#tui)
- [情報が沢山あるサイト](#many_golang_articles)
- [golang](#golang)
- [excel](#excel)
- [grpc](#grpc)
- [gcp](#gcp)

---

## basics

- [Go Official Page](https://golang.org/)
  - [Go 1.12 リリースノート](https://qiita.com/c-yan/items/5001121aa6a9566c7466)
  - [Go 1.13 リリースノート](https://qiita.com/c-yan/items/b2f5e5c168d517594eb2)
- [Go Documentation](https://golang.org/doc/)
- [Go Effective Go](https://golang.org/doc/effective_go.html)
- [Go Blog](https://blog.golang.org/)
  - [Go言語の文字列、バイト、ルーンと文字（翻訳）](https://qiita.com/KojiOhki/items/cf50c3afe52624b5f69e)
- [Go FAQ](https://golang.org/doc/faq)
- [Go Tour of Go](https://tour.golang.org/welcome/1)
- [Go Packages](https://golang.org/pkg/)
- [Go Playground](https://play.golang.org/)
- [Go Wiki](https://github.com/golang/go/wiki)
- [Go言語のGo紹介](https://qiita.com/matsutake/items/494275320c78986d1363)
  - 公式の [Go at Google: Language Design in the Service of Software Engineering](https://talks.golang.org/2012/splash.article) や [FAQ](https://golang.org/doc/faq) の和訳を交えながら、とても分かりやすく説明してくれている。
- [Go best practices, six years in](https://peter.bourgon.org/go-best-practices-2016/)
- [A theory of modern Go](https://peter.bourgon.org/blog/2017/06/09/theory-of-modern-go.html)
- [Go at Google: Language Design in the Service of Software Engineering](https://talks.golang.org/2012/splash.article)
  - Goが生まれた背景と言語の特徴について(Rob Pike氏)
- [Using Go Modules](https://blog.golang.org/using-go-modules)
  - [The Go Blog - Using Go Modules / Go Modulesを使う（和訳）](https://qiita.com/pokeh/items/139d0f1fe56e358ba597)
- [awesome-go](https://github.com/avelino/awesome-go)
  - AwesomeシリーズのGo版
- [project-layout](https://github.com/golang-standards/project-layout)
  - Go言語のプロジェクト構成についての資料
- [Go CodeReviewComments 日本語翻訳](https://qiita.com/knsh14/items/8b73b31822c109d4c497)
  - [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
- [Simple Go project layout with modules](https://eli.thegreenplace.net/2019/simple-go-project-layout-with-modules/)
  - Goのプロジェクトレイアウトについて分かりやすい説明がある
- [The Magic of Go Comments](https://blog.jbowen.dev/2019/09/the-magic-of-go-comments/)
- [GoDocドキュメントで知っていると便利な機能](https://qiita.com/lufia/items/97acb391c26f967048f1)
- [go doc の使い方・コメントを書いて、ちゃんと読む](https://qiita.com/ayasuda/items/53933c83d0fb7152c7e9)
- [チョットできるGoプログラマーになるための詳解GoDoc](https://qiita.com/shibukawa/items/8c70fdd1972fad76a5ce)
- [Why you should use go programming?](https://medium.com/@solaceinfotechh/why-you-should-use-go-programming-f6de093be3f3)
- [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
- [Clean Go Code](https://github.com/Pungyeon/clean-go-article)
- [Goにおける最適なディレクトリ構成はもはやこれだと思う](https://qiita.com/rema424/items/9ffbdf584b705cae6a19)

## github

- [wails](https://github.com/wailsapp/wails)
  - バックエンドにGo、フロントエンドにWebを採用するGuiフレームワーク
  - [wails.app](https://wails.app/)
- [godotenv](https://github.com/joho/godotenv)
  - ```.env```ファイルを扱うためのライブラリ
- [ratelimit](https://github.com/uber-go/ratelimit)
  - leaky-bucket rate limit algorithm
- [go-pretty](https://github.com/jedib0t/go-pretty)
- [urfave/cli](https://github.com/urfave/cli)
  - Goで恐らく一番有名なコマンドライン用ライブラリ
- [mitchellh/cli](https://github.com/mitchellh/cli)
  - 有名なコマンドライン作成用ライブラリの一つ（この上の urfave/cli の方が有名度は高い)
- [go-flags](https://github.com/jessevdk/go-flags)
- [clipboard](https://github.com/atotto/clipboard)
  - クリップボード用ライブラリ
- [redigo](https://github.com/gomodule/redigo)
  - redis 用ライブラリ
- [assets-life](https://github.com/shogo82148/assets-life)
  - 静的ファイル埋め込み用ライブラリ
- [go-sqlite3](https://github.com/mattn/go-sqlite3)
  - sqlite3 用ライブラリ
- [screenshot](https://github.com/kbinani/screenshot)
- [gotop](https://github.com/cjbassi/gotop)
  - Goで作成された```top```をリッチにした感じのCUIアプリケーション
- [bitvector](https://github.com/teivah/bitvector)
  - ビット演算用ライブラリ
- [goexec](https://github.com/shurcooL/goexec)
  - ```python -c``` のようにワンライナーを実行できるようにしてくれるライブラリ
- [hugo](https://github.com/gohugoio/hugo)
  - 静的サイトジェネレータ。世界最速とのこと。
- [litter](https://github.com/sanity-io/litter)
  - データを見やすい形で出力してくれるライブラリ
- [watermill](https://github.com/ThreeDotsLabs/watermill)
  - Watermill is a Go library for working efficiently with message streams.
- [v8go](https://github.com/rogchap/v8go)
  - GoからJavascriptを呼び出すライブラリ
- [ristretto](https://github.com/dgraph-io/ristretto)
- [packr](https://github.com/gobuffalo/packr)
  - バイナリに静的ファイルを埋め込むためのライブラリ
- [sprig](https://github.com/Masterminds/sprig)
- [parallelizer](https://github.com/shomali11/parallelizer)
  - go func などで待ち合わせなどを行う際にいちいち sync.WaitGroup などを使わなくてもよくなるライブラリ
- [script](https://github.com/bitfield/script)
  - Goでシェルライクなスクリプトをかけるようにしてくれるライブラリ
- [godu](https://github.com/viktomas/godu)
  - 指定されたディレクトリ配下の大きなサイズを持つファイルを探すツール
  - ```du``` コマンドみたいな感じ
- [gogs](https://github.com/gogs/gogs)
- [go-funk](https://github.com/thoas/go-funk)
  - go-linqやkoazeeと同じようなライブラリ
- [go-linq](https://github.com/ahmetb/go-linq)
  - GoでC#のLinqみたいな操作を出来るようになるライブラリ
- [koazee](https://github.com/wesovilabs/koazee)
  - 配列やスライスをJavaのStreamやC#のLinqみたいに扱えるようにしてくれるライブラリ
- [backoff](https://github.com/cenkalti/backoff)
  - Exponential backoff アルゴリズム
- [errors](https://github.com/pkg/errors)
  - このパッケージは現在メンテナンスモードにはいっている
  - Go1.13で errors パッケージになった
  - [Go2 error proposals](https://go.googlesource.com/proposal/+/master/design/go2draft.md)があるため
- [lazygit](https://github.com/jesseduffield/lazygit)
  - gocuiを利用してる git 操作のための tui アプリケーション
- [go-cmp](https://github.com/google/go-cmp)
  - 構造体の値比較用ライブラリ
  - [構造体などをテストするのに便利なgoogle/go-cmpの使い方](https://qiita.com/hgsgtk/items/bd78bada902c91745fa5)
- [ini](https://github.com/go-ini/ini)
  - Go から ini ファイルを扱うライブラリ
- [sftpgo](https://github.com/drakkan/sftpgo)
- [tinygo](https://github.com/tinygo-org/tinygo)
- [tview](https://github.com/rivo/tview)
  - CUI用ライブラリ
- [gocui](https://github.com/jroimartin/gocui)
  - CUI用ライブラリ
- [goban](https://github.com/eihigh/goban)
  - [Goで世界一シンプルなCUIライブラリ](https://qiita.com/eihigh/items/20de07f5d8cec0df17ab)とのこと
- [yaegi](https://github.com/containous/yaegi)
  - Go用のインタープリターライブラリ
- [vecty](https://github.com/gopherjs/vecty)
- [bokchoy](https://github.com/thoas/bokchoy)
  - Redisをバックエンドに利用しているシンプルなジョブキューライブラリ
- [go-echarts](https://github.com/chenjiandongx/go-echarts)
  - チャートライブラリ。高機能。
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
- [deque(Extremely fast ring-buffer deque)](https://github.com/gammazero/deque)
- [gore](https://github.com/motemen/gore)
  - Yet another Go REPL
  - Go言語用のREPL
- [tint](https://github.com/printzero/tint)
  - ターミナルの出力に色をつけてくれるライブラリ

## tui

- [Termbox-go](https://github.com/nsf/termbox-go)
  - [termbox](https://github.com/nsf/termbox) の Go版
- [tcell](https://github.com/gdamore/tcell)
  - termbox にインスパイアされたTUIライブラリ。機能多い。
- [termui](https://github.com/gizak/termui)
  - とても有名なライブラリ
- [tui-go](https://github.com/marcusolsson/tui-go)
- [gowid](https://github.com/gcla/gowid)
  - urwid にインスパイアされて作成されたTUIライブラリ
- [termdash](https://github.com/mum4k/termdash)
  - すごく多機能
- [gocui](https://github.com/jroimartin/gocui)
- [sampler](https://github.com/sqshq/sampler)
  - ライブラリではないけど、Goで作成されているTUIアプリ。とても高機能。YAMLで制御する。
  - termuiを土台にしている。

## many_golang_articles

- [Qiita - Goタグ](https://qiita.com/tags/go)
- [Go Advent Calendar 2015](https://qiita.com/advent-calendar/2015/go)
- [Go Advent Calendar 2016](https://qiita.com/advent-calendar/2016/go)
- [Go Advent Calendar 2017](https://qiita.com/advent-calendar/2017/go)
- [Go Advent Calendar 2018](https://qiita.com/advent-calendar/2018/go)
- [Go Advent Calendar 2019](https://qiita.com/advent-calendar/2019/go)
- [プログラミング言語 Go](https://text.baldanders.info/golang/)
  - 有用な情報がたくさんある
- [clean-go-article](https://github.com/Pungyeon/clean-go-article)
- [Go言語の勉強に役立つリンク集](https://qiita.com/nemui_/items/35064455964241b6307d)
- [Network Programming with Go by Jan Newmarch](http://tumregels.github.io/Network-Programming-with-Go/)
- [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/index.html)
- [Building Web Apps with Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/index.html)
- [Test-driven development with Go](https://leanpub.com/golang-tdd/read)
  - 書籍は有料だけどオンラインで無料で読める
- [learn-go-with-tests](https://github.com/quii/learn-go-with-tests)
- [Learn Go with tests](https://quii.gitbook.io/learn-go-with-tests/)
- [Attempting to Learn Go](https://github.com/shindakun/atlg)
- [AN INTRODUCTION TO PROGRAMMING IN GO](http://www.golang-book.com/books/intro)
- [Algorithms to Go](https://yourbasic.org/)
- [golangprograms](http://www.golangprograms.com/)
- [ultimate-go](https://github.com/hoanhan101/ultimate-go)
- [Go Language Patterns](http://www.golangpatterns.info/)
- [Go Bootcamp](http://www.golangbootcamp.com/book/frontmatter)
- [逆引きGolang](https://ashitani.jp/golangtips/index.html)
- [Learning Go](https://www.miek.nl/go/)
- [Go by Example](https://gobyexample.com/)
- [Go Language Tutorials](https://www.cybrhome.com/topic/go-language-tutorials)
- [Go Tutorial](https://www.tutorialspoint.com/go)
- [gotraining](https://github.com/ardanlabs/gotraining)
- [Vincent Blanchon@medium](https://medium.com/@blanchon.vincent)
- [Phil Pearl@medium](https://medium.com/@philpearl)
- [Can Tepakidareekul@medium](https://medium.com/@manus.can)
- [Kassim Damilola@medium](https://medium.com/@kdnotes)
- [Vladimir Vivien@medium](https://medium.com/@vladimirvivien)
- [Let's Go! Learn to Build Professional Web Applications With Golang](https://lets-go.alexedwards.net/)
  - 有料電子書籍
- [golangConcepts](https://github.com/premaseem/golangConcepts)
- [GoLang Tutorials](http://golangtutorials.blogspot.com/2011/05/table-of-contents.html)
- [algorithms](https://github.com/x899/algorithms)
- [Go Tutorials (Digital Ocean)](https://www.digitalocean.com/community/tags/go/tutorials)
- [Go newsletters gallery - Dor Moshe's Blog](https://dormoshe.io/newsletters/ag/golang)
- [TutorialEdge.net - Golang](https://tutorialedge.net/course/golang/)
- [golang-cheat-sheet](https://github.com/a8m/golang-cheat-sheet)
- [Practical Go](https://dave.cheney.net/practical-go)
- [A Journey With Go](https://medium.com/a-journey-with-go)
- [ゼロからはじめるGo言語](https://news.mynavi.jp/series/gogogo)
- [Go Patterns](http://tmrts.com/go-patterns/)
- [run.go](https://medium.com/rungo)
- [uber-go/guide](https://github.com/uber-go/guide/blob/master/style.md)
- [株式会社ライトコート(IT技術)](https://rightcode.co.jp/blog/information-technology)
- [Go-SCP](https://github.com/OWASP/Go-SCP)
  - secure coding practices guide

## golang

### lang-spec

- [「Go言語らしさ」とは何か？　Simplicityの哲学を理解し、Go Wayに沿った開発を進めることの良さ](https://employment.en-japan.com/engineerhub/entry/2018/06/19/110000)
- [Go言語のGo紹介](https://qiita.com/matsutake/items/494275320c78986d1363)
- [Go言語さわってみた](https://ktat.hatenadiary.jp/entry/20150621/1434893179)
- [Goを50時間勉強して分かったこと](https://qiita.com/kskinaba/items/5fc05d0233b989ae46c3)
- [Go言語の思想とエウレカでの5年間の活用](https://medium.com/eureka-engineering/advent-calendar-2019-go-b1535b174d59)
- [Go の命名規則](https://micnncim.com/post/2019/12/11/go-naming-conventions/)
- [Goのコード構成についての公式ドキュメントの日本語翻訳](https://qiita.com/wildmouse/items/cbae51fb4c0211b57c63)
- [Goのプロジェクトレイアウト](https://qiita.com/ohno2019/items/241541d0475338e26f6e)
- [Ultimate Setup for Your Next Golang Project](https://martinheinz.dev/blog/5)
- [図解 Go Slice Tricks](https://i-beam.org/2019/12/09/go-slice-tricks/)
- [Go言語のスライスで勘違いしやすいこところ](https://qiita.com/Kashiwara/items/e621a4ad8ec00974f025)
- [Go言語で構造体をコピーするときに気をつけること](https://qiita.com/kz23szk/items/8d60a4716f7e2de2e946)
- [Go言語のInterfaceの考え方、Accept interfaces,return structs](https://qiita.com/weloan/items/de3b1bcabd329ec61709)
- [GoのInterfaceの作法 "Accept Interfaces, Return structs"](https://y-zumi.hatenablog.com/entry/2019/07/28/035632)
- [The Principles of Versioning in Go](https://research.swtch.com/vgo-principles)
- [Go言語でメモリ上の大きさや配置を調べる](https://ota42y.com/blog/2015/05/06/go-struct-offset/)
- [Go言語のFunctional Option Pattern](https://qiita.com/weloan/items/56f1c7792088b5ede136)
  - [Self-referential functions and the design of options](https://commandcenter.blogspot.com/2014/01/self-referential-functions-and-design.html)
- [SOLID Go Design](https://dave.cheney.net/2016/08/20/solid-go-design)
- [SOLID principle in GO](https://medium.com/@s8sg/solid-principle-in-go-e1a624290346)
- [Best practices for a new Go developer](https://blog.rubylearning.com/best-practices-for-a-new-go-developer-8660384302fc)
- [簡単にできる！Goで書いたCLIツールを配布する方法](https://nukosuke.hatenablog.jp/entry/dist-go-cli)
- [Go ランタイムのデバッグをサポートする環境変数](https://qiita.com/mattn/items/e613c1f8575580f98194)
- [Go言語開発を便利にするMakefileの書き方](https://qiita.com/yoskeoka/items/317a3afab370155b3ae8)
- [Golang - Makefileの書き方](https://qiita.com/so_heee_/items/95c3c95da2104d895205)
- [いまさら人に聞けないmake入門](http://system.blog.uuum.jp/entry/make)
- [Using Makefile(s) for Go](https://danishpraka.sh/2019/12/07/using-makefiles-for-go.html)
- [Golang を使うなら Makefile を恐れるな](https://frasco.io/golang-dont-afraid-of-makefiles-785f3ec7eb32)
- [Golang: Don’t afraid of makefiles](https://sohlich.github.io/post/go_makefile/)
- [Makefiles for Go Developers](https://tutorialedge.net/golang/makefiles-for-go-developers/)

### mod (go modules)

- [Using Go Modules](https://blog.golang.org/using-go-modules)
- [Migrating to Go Modules](https://blog.golang.org/migrating-to-go-modules)
- [Publishing Go Modules](https://blog.golang.org/publishing-go-modules)
- [Go Modules: v2 and Beyond](https://blog.golang.org/v2-go-modules)
- [和訳: Go += Package Versioning (Go & Versioning, Part 1)](https://qiita.com/nekketsuuu/items/60634417e6279ccfd95b)
- [和訳: A Tour of Versioned Go (vgo) (Go & Versioning, Part 2)](https://qiita.com/nekketsuuu/items/589bc29f00b507492a96)
- [和訳: Semantic Import Versioning (Go & Versioning, Part 3)](https://qiita.com/nekketsuuu/items/2dcad7dde29171e1fe3f)
- [GoにおけるSemantic versioningとgo.modにある+incompatibleについて](https://qiita.com/Tommy_/items/32d2d0d9f56365ee61fc)
- [Go Modules and Major Versions](https://codeengineered.com/blog/2019/go-mod-major-versions/)
- [how to upgrade go mod to v2 or higher version?](https://stackoverflow.com/questions/55096443/how-to-upgrade-go-mod-to-v2-or-higher-version)


### concurrent

- [Go が他の多くの言語での非同期プログラミングよりも優れている理由](https://qiita.com/methane/items/5ad7c092c0d426db4ab5)
- [Share Memory By Communicating](https://blog.golang.org/share-memory-by-communicating)
  - 公式ブログ記事
  - ```Do not communicate by sharing memory; instead, share memory by communicating.```
- [package errgroup](https://godoc.org/golang.org/x/sync/errgroup)
  - 公式が出している追加パッケージの一つ。 sync.WaitGroup の エラー制御 考慮版みたいな感じ
- [Go 言語における並行処理の構築部材](https://motemen.hatenablog.com/entry/2016/05/go-concurrent-building-blocks)
- [Go の並行処理](http://jxck.hatenablog.com/entry/20130414/1365960707)
- [複数のGoroutineをWaitGroup（ErrGroup）で制御する](https://blog.toshimaru.net/goroutine-with-waitgroup/)
- [sync.ErrGroupで複数のgoroutineを制御する](https://deeeet.com/writing/2016/10/12/errgroup/)
- [Go言語のゴルーチンとWaitGroupを使った並行処理](https://qiita.com/moriyatto/items/e4efcae76fc5cb845a87)
- [Curious Channels](https://dave.cheney.net/2013/04/30/curious-channels)
- [Learning Go’s Concurrency Through Illustrations](https://medium.com/@trevor4e/learning-gos-concurrency-through-illustrations-8c4aff603b3)
- [Go Concurrency Patterns: Context](https://blog.golang.org/context)
- [Go1.7のcontextパッケージ](https://deeeet.com/writing/2016/07/22/context/)
- [golangでcontextパッケージを使う](https://www.write-ahead-log.net/entry/2017/04/07/214420)

### error-handling

- [Defer, Panic, and Recover](https://blog.golang.org/defer-panic-and-recover)
- [Error handling and Go](https://blog.golang.org/error-handling-and-go)
- [Errors are values](https://blog.golang.org/errors-are-values)
- [Working with Errors in Go 1.13](https://blog.golang.org/go1.13-errors)
- [Golang: How to handle Errors in v1.13](https://medium.com/@felipedutratine/golang-how-to-handle-errors-in-v1-13-fda7f035d027)
- [Go1.13以後のエラーハンドリングについて語ろう](https://speakerdeck.com/ciarana/lets-talk-about-error-handling-after-go-1-13)
- [Go 1.13時代のエラー実装者のお作法](https://qiita.com/shibukawa/items/e633e426a6e67ea2e830)
- [運用を意識したGo言語でのエラーハンドリング/ロギング](https://qiita.com/nayuneko/items/dea02377b797c2a52053)
- [Panicking the right way in Go](https://blog.trailofbits.com/2019/06/26/panicking-the-right-way-in-go/)
- [Error Handing with Go-Lang](https://medium.com/@kdnotes/error-handing-with-go-lang-58f2dc883684)
- [Go言語 runtime.Callerを使ってメッセージやerrorにソースファイル名、行番号を含める](https://qiita.com/h6591/items/468be2f4524ccc888795)
- [Golang | Error Handling](https://medium.com/@tonaco.braulio/golang-error-handling-4a96ab8db417)
- [Programming with errors](https://peter.bourgon.org/blog/2019/09/11/programming-with-errors.html)
- [A Look At Go 1.13 Errors](https://medium.com/onefootball-locker-room/a-look-at-go-1-13-errors-9f6c9f6accb6)

### logging

- [軽量かつ高速なロガーzapを導入する](https://qiita.com/RyoMa_0923/items/a765d2687531c6d322ec)
- [【Go×ログ】logrusの使い方を簡単に分かりやすくまとめてみた](https://qiita.com/gold-kou/items/3143ab4622acacd33f8d)
- [運用を意識したGo言語でのエラーハンドリング/ロギング](https://qiita.com/nayuneko/items/dea02377b797c2a52053)
- [logutils](https://github.com/hashicorp/logutils)
- [file-rotatelogs](https://github.com/lestrrat-go/file-rotatelogs)
- [logf](https://github.com/spiegel-im-spiegel/logf)
- [zap](https://github.com/uber-go/zap)

### image

- [Go言語の標準パッケージだけで画像処理をする その１ （入出力）](https://qiita.com/ikeponsu/items/808a83d2f3bcf3ad95f3)
- [Go言語の標準パッケージだけで画像処理をする その２ （回転、反転）](https://qiita.com/ikeponsu/items/0beb5387882eb1f9d525)

### file-io

- [Using io.Reader/io.Writer in Go to stream data](https://dev.to/flowup/using-io-reader-io-writer-in-go-to-stream-data-3i7b)
- [Go言語での文字列操作に関して覚えておきたいこと](https://qiita.com/masalennon/items/a084b1fd9f528d6fe5f2)
- [Golang による文字エンコーディング変換](https://qiita.com/spiegel-im-spiegel/items/2e475b48226330aa5570)

### networking

- [GoでTCPソケットを使ったときのメモ](https://qiita.com/t10471/items/424c16f1bd7f374f51b7)
- [How to test TCP/UDP connections in Go - Part 1](https://dev.to/williamhgough/how-to-test-tcpudp-connections-in-go---part-1-3bga)
- [How to test TCP/UDP connections in Go - Part 2](https://dev.to/williamhgough/how-to-test-tcpudp-connections-in-go---part-2-2960)

### testing

- [Goのtestingパッケージの基本を理解する](https://qiita.com/taisa831/items/85fea8d970bcadd796b9)
- [Goのtestを理解する in 2018](https://budougumi0617.github.io/2018/08/19/go-testing2018/)
- [Goのtestを理解する in 2019](https://budougumi0617.github.io/2019/10/30/go-testing2019/)
- [Goでシンプルに単体テストを書く](https://qiita.com/hz1_d/items/bfbcb508adbf8a99ad58)
- [テストを実行する（go testの利用）](https://www.yoheim.net/blog.php?q=20170903)
- [Testable Examples in Go](https://blog.golang.org/examples)
- [Using Subtests and Sub-benchmarks](https://blog.golang.org/subtests)
- [TableDrivenTests](https://github.com/golang/go/wiki/TableDrivenTests)
- [Using Go Flags in Tests](https://blog.jbowen.dev/2019/08/using-go-flags-in-tests/)
- [7 Testing Techniques for Your Golang Codebase](https://building.lang.ai/7-testing-techniques-for-your-golang-codebase-77649a96a1c9)
- [GoMock vs. Testify: Mocking frameworks for Go](https://blog.codecentric.de/2019/07/gomock-vs-testify/)
- [Using Go Interfaces for Testable Code](https://medium.com/swlh/using-go-interfaces-for-testable-code-d2e11b02dea)
- [Go言語でユニットテスト, テストしやすいコードとモックを書く](https://qiita.com/hiroyky/items/4a9be463e752d5c0c41c)
- [How to Test Local Changes with Go Mod](https://medium.com/@teivah/how-to-test-a-local-branch-with-go-mod-54df087fc9cc)

### wasm

- [(Tiny)Go to WebAssembly](https://dev.to/sendilkumarn/tiny-go-to-webassembly-5168)
- [Go × WebAssemblyで電卓のWebアプリを作ってみた](https://buildersbox.corp-sansan.com/entry/2019/02/14/113000)
- [GoでChrome拡張を作った話](https://qiita.com/ramenjuniti/items/20a42be5f157e5851f12)

### system_programming

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

### misc

- [Golang Templates Cheatsheet](https://curtisvermeeren.github.io/2017/09/14/Golang-Templates-Cheatsheet)
- [How I Embedded Resources in Go](https://levelup.gitconnected.com/how-i-embedded-resources-in-go-514b72f6ef0a)
- [golangでDBの接続文字列にパスワードを含めない安全な方法。](https://qiita.com/_kyamasan/items/8b5673f5927dc7f741bf)
- [Go 言語で学ぶ『暗号技術入門』Part 3 -CBC Mode-](https://skatsuta.github.io/2016/03/06/hyuki-crypt-book-go-3/)
- [Go 言語で学ぶ『暗号技術入門』Part 2 -AES-](https://skatsuta.github.io/2016/01/19/hyuki-crypt-book-go-2/)
- [Go 言語で学ぶ『暗号技術入門』Part 1 -DES, Triple DES-](https://skatsuta.github.io/2016/01/02/hyuki-crypt-book-go-1/)
- [Go のバイナリに静的ファイルを埋め込む assets-life を使ってみた](https://qiita.com/akif999/items/c892448b56615503e100)
- [コマンドプロンプトの文字幅をキャリブレーションして、崩れない TUI 画面を作ろう](https://qiita.com/zetamatta/items/f823aef67a62de37c870)
- [golang で手軽にコマンド作成](https://qiita.com/Haruki-Miyagi/items/6fe9e6ce01e310da1cf2)
- [Abstraction Antipatterns in Go](https://medium.com/weave-lab/abstraction-antipatterns-in-go-a85d6703c0e3)
- [40+ practical string tips [cheat sheet]](https://yourbasic.org/golang/string-functions-reference-cheat-sheet/)
- [The Top 10 Most Common Mistakes I’ve Seen in Go Projects](https://itnext.io/the-top-10-most-common-mistakes-ive-seen-in-go-projects-4b79d4f6cd65)
- [ビルドする際にバージョン情報を埋め込む](https://qiita.com/harukasan/items/37698ec799678c12e71d)
- [Goを学ぶときにつまずきやすいポイントFAQ](https://future-architect.github.io/articles/20190713/)
- [Learning Golang — from zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/)
- [Goで固定長フォーマットを扱う](https://qiita.com/Hiraku/items/d1f80bdd49efba301c54)
- [Why Golang is Better Than Other Programming Languages?](https://www.consagous.com/blog/why-golang-is-better-than-other-programming-languages/)
- [10 things I like about Go](https://medium.com/@meeusdylan/go-10-reasons-i-enjoy-go-ef3c3352174)
- [Array and Slices In GO](https://medium.com/@rahulrd005/introduction-to-array-and-slices-in-go-14b7d08a8f1f)
- [Go: Memory Management and Allocation](https://medium.com/a-journey-with-go/go-memory-management-and-allocation-a7396d430f44)
- [Go言語で日付処理](https://mattn.kaoriya.net/software/lang/go/20130620173712.htm)
- [loggingについて話そう](https://qiita.com/methane/items/cedbf546ae2db8a63c3d)
- [Slice Tricks in Go](https://medium.com/@rocketlaunchr.cloud/slice-tricks-in-go-1edc21ae9109)
- [Streaming IO in Go](https://medium.com/learning-the-go-programming-language/streaming-io-in-go-d93507931185)
- [Go 言語の環境変数管理](https://text.baldanders.info/golang/go-env/)
- [Go: How Does the Garbage Collector Mark the Memory?](https://medium.com/a-journey-with-go/go-how-does-the-garbage-collector-mark-the-memory-72cfc12c6976)
- [【Go】コーディングTips](https://qiita.com/kskumgk63/items/2b63f63ebd69b7b91c08)
- [50 Shades of Go: Traps, Gotchas, and Common Mistakes for New Golang Devs](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/)
- [GolangのSliceを関数の引数に渡した時の挙動](https://christina04.hatenablog.com/entry/2017/09/26/190000)
- [Using Golang as a scripting language](https://dev.to/eminetto/using-golang-as-a-scripting-language-jl2)
- [Program Structure and Composability](https://blog.mediocregopher.com/2019/08/02/program-structure-and-composability.html)
- [Context Package Semantics In Go](https://www.ardanlabs.com/blog/2019/09/context-package-semantics-in-go.html)
- [Instrumenting Go applications](https://banzaicloud.com/blog/instrumenting-go-applications/)
- [Breadth-first search using Go standard library](https://cybernetist.com/2019/03/09/breadth-first-search-using-go-standard-library/)
- [Go Docker](https://medium.com/monstar-lab-bangladesh-engineering/go-docker-2843a9339913)
- [エラーの種類によって処理を分けるBESTな方法](https://qiita.com/yoshinori_hisakawa/items/15bf0307245744deb4fc)
- [Goのtimeパッケージチートシート](https://qiita.com/wMETAw/items/2c3120d1338c646ecfba)
- [Golang syntax cheat sheet](https://medium.com/@phuctm97/golang-syntax-cheat-sheet-424a1ec6ae30)
- [Using io.Reader/io.Writer in Go to stream data](https://dasio.hashnode.dev/using-of-ioreaderiowriter-in-go-to-stream-data-ck0v22mvg0005xes1gp13f5pg)
- [Introducing Ristretto: A High-Performance Go Cache](https://blog.dgraph.io/post/introducing-ristretto-high-perf-go-cache/)
- [Go 言語の環境変数管理](https://text.baldanders.info/golang/go-env/)
- [Functional Option Pattern](https://blog.web-apps.tech/go-functional-option-pattern/)
- [Golang Receiver vs Function Argument](https://grisha.org/blog/2016/09/22/golang-receiver-vs-function/)
- [struct に依存しない処理は function に切り出すのか、method に切り出すのか](https://www.pospome.work/entry/2017/01/16/233351)
- [Concurrency, Goroutines and GOMAXPROCS](https://www.ardanlabs.com/blog/2014/01/concurrency-goroutines-and-gomaxprocs.html)
- [Parallel processing in golang](https://stackoverflow.com/questions/25106526/parallel-processing-in-golang)
- [A visual guide to Go Memory Allocator from scratch (Golang)](https://blog.ankuranand.com/2019/02/20/a-visual-guide-to-golang-memory-allocator-from-ground-up/)
- [GO MEMORY MANAGEMENT](https://povilasv.me/go-memory-management/)
- [Simple techniques to optimise Go programs](https://stephen.sh/posts/quick-go-performance-improvements)

- [goroutineとチャネルの動きを図を使って理解する(和訳)](https://qiita.com/hirano00o/items/828393342efcd80aa2e6)
  - [A visual introduction to golang concurrency and goroutines](https://stackedco.de/a-visual-introduction-to-golang-goroutines)
- [リトライ処理の効率的アプローチ「Exponential Backoff」の概要とGoによる実装](https://qiita.com/po3rin/items/c80dea298f16a2625dbe)
- [Goといえばチャネルでしょ！！！　第3弾](https://qiita.com/besood/items/62838cc3f0bdadbf3f29)
- [Golangでゴルーチンを触ってみる　第二弾](https://qiita.com/besood/items/fe48f295c2e1816f5a14)
- [俺もgolangでゴルーチン触ってみたい！！](https://qiita.com/besood/items/450c39404ddec4b68936)
- [急いで学ぶGo lang#7 range・Array・slice・map](https://dev.classmethod.jp/go/golang-7/)
- [急いで学ぶGo lang#6 インターフェイス](https://dev.classmethod.jp/go/golang-6/)
- [急いで学ぶGo lang#5 構造体](https://dev.classmethod.jp/server-side/language/golang-5/)
- [急いで学ぶGo lang#4 関数・ポインタ・制御構文](https://dev.classmethod.jp/server-side/language/golang-4/)
- [急いで学ぶGo lang#3 まずは基本構文](https://dev.classmethod.jp/server-side/language/golang-3/)
- [急いで学ぶGo lang#2 IntelliJ IDEAでGo開発](https://dev.classmethod.jp/server-side/language/golang-2/)
- [急いで学ぶGo lang#1 概要とセットアップ](https://dev.classmethod.jp/server-side/language/golang-1/)
- [Singleton vs Multiton](https://medium.com/@hafizputraludyanto/singleton-vs-multiton-golang-1fed3e984c36)
- [Ultimate Golang String Formatting Cheat Sheet](https://medium.com/@arindamroy/ultimate-golang-string-formatting-cheat-sheet-234ec92c97da)
- [Understanding Real-World Concurrency Bugs in Go](https://songlh.github.io/paper/go-study.pdf)
- [Migrating to Go Modules](https://blog.golang.org/migrating-to-go-modules)
- [Go の channel に出てくる矢印の意味](https://qiita.com/TsuyoshiUshio@github/items/d94a3d0f934bde6d6aed)
- [Notes on TCP keepalive in Go](https://thenotexpert.com/golang-tcp-keepalive/)
- [Simple server for a binary protocol in Golang](https://thenotexpert.com/simple-server-binary-protocol-golang/)
- [Notes on various features of Golang](https://thenotexpert.com/golang-advanced/)
- [Slices in Go. Expandable or not?](https://thenotexpert.com/golang-slices/)
- [Typed nil in Go... wait, what?](https://thenotexpert.com/golang-typed-nils/)
- [How To Create Your Own CLI — With Golang](https://itnext.io/how-to-create-your-own-cli-with-golang-3c50727ac608)
- [Learn Go By Building a Command-Line App](https://medium.com/xebia-engineering/learn-go-by-building-a-command-line-app-bedf32980c0b)
- [Work queue with Go and RabbitMQ](https://medium.com/@masnun/work-queue-with-go-and-rabbitmq-b8c295cde861)
- [Go言語で書かれたアプリケーションをダウンタイムゼロでデプロイする方法](https://qiita.com/Ryoma0413/items/53006cc1b8f6a5174751)
- [Go言語の埋め込みについて4つのポイントでまとめてみた](https://qiita.com/momotaro98/items/4f6e2facc40a3f37c3c3)
- [Go routine without a panic](https://medium.com/@mourya.g9/go-routine-without-a-panic-2b03e0546683)
- [Linked Lists — in Go!](https://medium.com/@priyanshsangule/data-structures-with-go-linked-list-d1b11c1a90e0)
- [構造体オブジェクト初期化時にフィールド名を指定することを強制する](https://budougumi0617.github.io/2019/08/17/must-use-key-in-struct-initialize/)
- [Pass by reference vs pass by value](https://forum.golangbridge.org/t/pass-by-reference-vs-pass-by-value/15005)
  - めっちゃ分かりやすい図がある
- [A Goroutines Gotcha](https://medium.com/@psinghal04/a-goroutines-gotcha-7d7441c7758f)
- [Go lang Reflection?](https://medium.com/@heshani.samarasekara/go-lang-reflection-aa6089c93cd8)
- [【Golang】コアラのように怠惰でチンパンジーのように賢い、高速配列操作ライブラリ「Koazee」使ってみた](https://qiita.com/nqdior/items/e225eae820d6157dc05b)
- [LinkList in GoLang (Delete Element)](https://medium.com/@nitaandroid121/linklist-in-golang-delete-element-371c1289038)
- [LinkList in GOlang (Adding Element)](https://medium.com/@nitaandroid121/linklist-in-golang-adding-element-4d5c70ab6c17)
- [The Simplest Way to Handle Timeouts in Golang](https://medium.com/@arindamroy/the-simplest-way-to-handle-timeouts-in-golang-11e371dc6188)
- [なぜ私達は Python から Go に移行したのか](https://frasco.io/why-we-switched-from-python-to-go-19581e27de7c)
- [Golangでログを吐くコツ](https://www.kaoriya.net/blog/2018/12/16/)
- [golang でループを手っ取り早く並列化する方法](https://www.kaoriya.net/blog/2013/07/08/)
- [設定ファイルとしての main.go](https://www.kaoriya.net/blog/2017/12/10/)
- [SHOULD I GO? THE PROS AND CONS OF USING GO PROGRAMMING LANGUAGE](https://mobilejazz.com/blog/should-i-go-the-pros-and-cons-of-using-go-programming-language/)
- [Go 1.13 に向けて知っておきたい Go Modules とそれを取り巻くエコシステム](https://syfm.hatenablog.com/entry/2019/08/10/170730)
- [The syntax of `go build` command](https://forum.golangbridge.org/t/the-syntax-of-go-build-command/14880)
- [Learn Golang Basic Syntax in 10 Minutes](https://medium.com/@manus.can/learn-golang-basic-syntax-in-10-minutes-48608a315896)
- [Creational Design Pattern in GO](https://medium.com/@rojace.shrestha/creational-design-pattern-in-go-b78cce98f328)
- [Methods in Go! Confusing ?](https://medium.com/@milinddhoke.in/methods-in-go-confusing-52bf589659c3)
- [7 Easy functional programming techniques in Go](https://dev.to/deepu105/7-easy-functional-programming-techniques-in-go-3idp)
- [mapの競合状態のはなし](http://imagawa.hatenadiary.jp/entry/2019/08/14/090000)
- [Golang patterns: Leaky goroutines and how to clean them](https://medium.com/@manoj563125/golang-leaky-goroutines-and-how-to-clean-them-30b505417028)
- [[Go] function decorator in http.HandleFunc](https://medium.com/@yulang.chu/go-function-decorator-in-http-handlefunc-6c9b20d003ad)
- [[Go] Function in Strategy pattern](https://medium.com/@yulang.chu/go-function-in-strategy-pattern-efd088d345de)
- [[Go] Function as arguments or returned value: Some use cases](https://medium.com/@yulang.chu/go-function-as-arguments-or-returned-value-some-use-cases-6d5bc15a84ab)
- [[Go] Stack or heap(4): improving heap performance with sync.Pool](https://medium.com/@yulang.chu/go-stack-or-heap-4-improving-heap-performance-with-sync-pool-1f798a16f126)
- [[Go] Stack or heap(3): non-inline struct could cause escape to heap](https://medium.com/@yulang.chu/go-stack-or-heap-3-non-inline-struct-could-cause-escape-to-heap-a443e4b1213)
- [[Go] Stack or heap(2): slices which keep in stack have limitation of size](https://medium.com/@yulang.chu/go-stack-or-heap-2-slices-which-keep-in-stack-have-limitation-of-size-b3f3adfd6190)
- [[Go] Stack or heap(1): does it matter?](https://medium.com/@yulang.chu/go-stack-or-heap-1-does-it-matter-67144803deb3)
- [One Program Written in Python, Go, and Rust](http://www.nicolas-hahn.com/python/go/rust/programming/2019/07/01/program-in-python-go-rust/)
- [(Tiny)Go to WebAssembly](https://dev.to/sendilkumarn/tiny-go-to-webassembly-5168)
- [Routing with Channel and Goroutine (P2)](https://medium.com/@owlwalks/routing-with-channel-and-goroutine-p2-519e17ec519d)
- [How would you organize your goroutine and channel? (P1)](https://medium.com/@owlwalks/how-would-you-organize-your-goroutine-and-channel-p1-e6e3c698f90c)
- [Programming business processes in Golang](https://medium.com/@bykovskimichael/programming-business-processes-in-golang-f3612108d16b)
- [Go Modules In Real Life](https://chipkeyes.me/go-modules-in-real-life/)
- [Goを書く時に気にすべきこと(よりリーダブルなコードにするために)](https://qiita.com/hiromichi_n/items/80340eee3d752fed6a8d)
- [名前付き戻り値との正しい付き合い方](https://medium.com/eureka-engineering/named-return-values-7f485d867df0)
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

## excel

- [Go言語でExcelファイルを処理するのが超簡単だった](http://pineplanter.moo.jp/non-it-salaryman/2017/06/18/go-read-excel/)
- [Go言語でExcel処理パートⅡ シート内の値をすべて表示する](http://pineplanter.moo.jp/non-it-salaryman/2017/06/20/go-read-excel2/)
- [Go言語でExcel処理パートⅢ ファイルを新規作成し書き込む](http://pineplanter.moo.jp/non-it-salaryman/2017/06/21/go-read-excel3/)
- [Go言語でExcelファイルから特定データを抽出するアプリ作ったよ](http://pineplanter.moo.jp/non-it-salaryman/2017/06/23/go-extract-excel/)
- [Using Golang to Read and Create Excel files](https://medium.com/cloud-native-the-gathering/using-golang-to-create-and-read-excel-files-7e0c10a31583)

## grpc

- [Protocol Buffers / Go Generated Code（和訳）](https://qiita.com/takegamm/items/3b7a2c6e9c56ab58c909)
- [Golang gRPC — Part 2 — Simple chat application with gRPC](https://medium.com/@viethapascal/golang-grpc-part-2-simple-chat-application-with-grpc-ef6a6c0eea32)
- [Golang gRPC — Part 1 — gRPC and protobuf syntax](https://medium.com/@viethapascal/golang-grpc-part-1-grpc-and-protobuf-syntax-d7b03cc24815)
- [Guaranteed Delivery with gRPC Streams](https://blog.maddevs.io/guaranteed-delivery-with-grpc-streams-dc847ead7e6e)
- [Go + gRPCによるマイクロサービス構築](https://user-first.ikyu.co.jp/entry/2019/06/17/100000)
- [いまさらだけどgRPCに入門したので分かりやすくまとめてみた](https://qiita.com/gold-kou/items/a1cc2be6045723e242eb)

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

