# GraduationProject_RUNTEQ

### ■サービス概要
どんなサービスなのかを３行で説明してください。
- 思いつきメモをアウトプットするサービス
- アイデア・感情など自分の言葉でアウトプットしておきたいものをメモする
- メモを書きっぱなしにせず、振り返ることで自己分析を促進するサービス

### ■ このサービスへの思い・作りたい理由
このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。
このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。
- 今までメモやTIL、SNSなどで自分の言葉でアウトプットしてきたが、書きっぱなしになっていた
- 何かと慌ただしい日々で振り返り、自分と向き合う時間が少なくなっている
- 就活・転職、体調不良など、振り返るその時がいざ来たとき、まとめてやるのは結構ハードではないか
- 以前より10年日記をつけており自分の言葉を残すことの大切さを感じている
- 情報過多、ストレス社会と言われる現代でも、その日・その一瞬の自分の本音を記録し、自分を大切にしたい
- セルフメンタルケアや自己分析のために、手軽に振り返ることができるツールを作りたい　

### ■ ユーザー層について
- スマホで思いつきメモを気軽に残し、活用したい人<br>
  : 思いつきは必ずどこかで繋がるが、振り返りハードルが高く、手軽に振り返りができるサービスが必要と考えたため
- 自己分析・セルフメンタルケアに興味がある人<br>
  : 自分の思考や感情を吐き出すサービスはあるが、自分の言葉という大きな財産の活用が不十分と考えたため

### ■サービスの利用イメージ
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。
- 思いついたことをスマホでメモし、ジャンル・タグ分け機能活用により手軽にメモの管理・振り返りが可能
- 思いつきメモはいつかどこかで繋がるため、タグで紐付けたメモを振り返り
  書きっぱなし防止・活用することで、思考整理のサポートや自己分析、セルフメンタルケアへ繋がる
- 振り返りの方法は、<br>
  1. ジャンル・タグを活用して振り返りたいメモを抽出・選択する<br>
  2. 紐付けをしたメモへ、振り返りメモを作成する<br>
  3. 振り返りが完了したメモはステータスを自動で完了とする<br>
- 振り返り時期が来たメモは通知し、振り返りをサポート
  - 問いかけ形式の通知により、スムーズに振り返りへ入れる

### ■ ユーザーの獲得について
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。
- X共有機能による宣伝
  - 書きっぱなしのメモを何件振り返ったかをXで共有し、サービスを認知してもらい有用性も伝える
  - 連続投稿日数をXで共有し、サービスの継続性を伝える

### ■ サービスの差別化ポイント・推しポイント
似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。
- ジャンル・タグ機能によるメモ管理<br>
  : デジタルではスマホのメモ機能、NotionやX（Twitter）、アナログではノートなど自分の思考や感情を残すサービスが存在するが、当サービスではジャンル・タグ機能により、分類ごとに整理して振り返る機能が推しポイント
- 問いかけ形式の通知により振り返りが簡単<br>
  : メモのステータスと作成日時、ジャンル・タグの情報を取得し、未完了・一定期間以上経過したメモをAI要約・問いかけ形式のテキストで返して通知する機能が差別化ポイント

### ■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。
#### MVPまで
- ユーザー登録機能
  -氏名
  -メールアドレス
  -パスワード
  -プロフィール画像

- 認証機能(sorceryで検証予定)
  - ログイン
  - ログアウト

- ユーザーページ
  - ユーザー名
  - メモの一覧表示
    - 全て
    - ジャンル別
    - タグ別
    - 日付別
    - 完了済みメモ
    - 振り返りメモ
  - メモの検索機能(Ransack予定)
    - キーワード検索
    - ジャンル検索
    - タグ検索
    - 日付検索

- メモ機能
  - 作成
    - アプリでの作成
  - 編集
    - メモの編集
    - ジャンルの編集
    - タグの編集
  - 削除

- 振り返り機能
  - 紐付けて振り返りメモ作成
    - メモを選択(複数可能)
    - 分類(ジャンル・タグ)を選択

- X共有機能
  - 振り返りメモ作成後にXへ共有

#### 本リリース
- 認証機能
  - SNS認証（Google,LINE）
  - パスワードリセット
- ユーザーページ
  - プロフィール画像(S3導入予定)
  - 完了設定
- メモ機能
    - Lineからの作成
- 振り返り機能
  - 振り返りを促すLINE通知
    - 例:Dailyタグの未完了メモが7個以上で通知
    - 例:指定タイミング(曜日や時間)に通知
- X共有機能
  - 連続投稿祝い通知とX共有


### ■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。
- LINE Messaging API
  -認証機能
  - メモ機能
    - Lineからの作成
  - 振り返り機能
    - 振り返りを促すLINE通知
      - 例:Dailyタグの未完了メモが7個以上で通知
      - 例:指定タイミング(曜日や時間)に通知
- OpenAI API([Natural Language APIも検討中](https://www.topgate.co.jp/blog/google-service/13039))
  - 問いかけ形式の振り返り通知
    - ステータスと作成日時、ジャンル・タグの情報を取得し、未完了・一定期間以上経過したメモを抽出
    - OpenAIで要約・問いかけ形式のテキストで返してユーザーへ通知

### ■使用予定の技術スタック
使用予定の技術スタックをREADMEに記載してください。<br>
| category | 技術 |
| ‐‐‐ | ‐‐‐ |
| フロントエンド | Rails 7.1.3.2 (Hotwire/Turbo), TailwindCSS, DaisyUI |
| バックエンド | Rails 7.1.3.2 (Ruby 3.2.2 ) |
| データベース | Mysql2 |
| 認証 | sorcery |
| 環境構築 | Docker |
| インフラ | heroku |
| Web API | LINE Messaging API、OpenAI API |

### (全体の機能概要)
- ユーザー登録機能
  -氏名
  -メールアドレス
  -パスワード
  -プロフィール画像

- 認証機能(sorceryで検証予定)
  - SNS認証（Google,Line）
  - ログイン
  - ログアウト
  - パスワードリセット

- ユーザーページ
  - プロフィール画像(S3導入予定)
  - ユーザー名
  - メールアドレス
  - パスワードリセット
  - メモの一覧表示
    - 全て
    - ジャンル別
    - タグ別
    - 日付別
    - 完了済みメモ
    - 振り返りメモ
  - メモの検索機能(Ransack予定)
    - キーワード検索
    - タグ検索
    - ジャンル検索
    - 日付検索

- メモ機能
  - 作成
    - アプリでの作成
    - Lineからの作成
  - 編集
    - メモの編集
    - ジャンルの編集
    - タグの編集
    - 完了設定
  - 削除

- 振り返り機能
  - 紐付けて振り返りメモ作成
    - メモを選択(複数可能)
    - 分類を選択
  - 通知機能
    - 振り返りを促す通知
      - 例:Dailyタグの未完了メモが7個以上で通知
      - 例:指定タイミング(曜日や時間)に通知
    - 問いかけ形式の振り返り通知

- X共有機能
  - 振り返りメモ作成後にXへ共有
  - 連続投稿祝い通知とX共有