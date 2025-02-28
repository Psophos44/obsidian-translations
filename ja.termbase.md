# このドキュメントについて

Obsidianの翻訳作業に興味を持っていただきありがとうございます。ヘルプドキュメントとユーザーインターフェースの両方で基本的な用語の整合性を保ちつつ、非同期的な共同作業を進めるために `ja.termbase.md` を用意しました。日本語翻訳での表記ルールや語彙の対応についてはこのファイルを参照してください。また、フォーラムやDiscord上での英語による議論についていきたい人のためにも翻訳前のオリジナルの用語を周知すべくリストアップしています。

現在、Obsidianは開発中であり、新しい機能が追加されるにつれて翻訳すべきテキストも増えます。まだ翻訳されていない用語やテキストを見つけた場合には、是非翻訳してみてください。タイポや誤訳等のミスを発見した場合にもプルリクエストを作成して提出してみてください。

ただし、現在翻訳されている用語とこれから翻訳される用語の一貫性を保つためにも、翻訳する際にはこのファイルにリストアップされている用語をなるべく参照するようにしてください。どのように翻訳するべきか分からない場合や議論となるような用語、気になる用語がある際には語彙対応表セクションの最後に追加してください。

すでに翻訳されている用語がふさわしくないと感じる場合や、その用語について議論をしたい場合はGithub上でissueを作成するか、[Discord](https://discord.gg/veuWUTm)の日本語チャンネルや[フォーラム](https://forum.obsidian.md/)などでトピックを作成してみてください。

用語のリストは**アルファベット順**に並ぶようにお願いします。

---

## 翻訳作業の指標

ヘルプドキュメントとUIの翻訳の両方において一貫した用語対応と表現を心がけてください。特に頻出度の高い表現や語句について、現在のドキュメントに表現搖れがある場合には、テキストエディタの置換機能などを使って統一した表現に置き換えてください。その際には、どちらの表現が既存のドキュメントに多いか、またどちらが分かりやすいかなどを考慮してから変えるようにしてください。

特に｢すべて｣などの副詞は複数回コマンド名で使われており、コマンドパレットでの検索のしやすさを考慮してひらがな表記になっています。そういったUIの表現を優先し、その表現がヘルプドキュメントに反映されるようにしてください。ルールを変更する場合には、UIのファイル(`ja.json`)と日本語ヘルプドキュメント(`ja/`)、語彙対応表と表記ルール(`ja.termbase.md`)のすべてで置き換えてください。

コマンド名の翻訳に関しては、コマンドが何を意味しているのかが分かりやすく、｢すべて｣や｢新規｣などの一貫した表現や｢ペイン｣や｢ノート｣などの統一された用語でコマンドパレットの検索に引っかかるように翻訳を行ってください。

## モバイル版の翻訳について

Obsidian MobileはObsidian Desktopとほぼ同じUIであり、`ja.json` がそのまま使われています。モバイル版独自の翻訳については `ja.json` にある `mobile-toolbar` の項目を参照してください。

## 語彙対応表

### 用語の対応

|Original term|Japanese translation|
|-|-|
alias | エイリアス
appearance | 外観
arrows | 矢印
audio file | 音声ファイル
backlinks | バックリンク
blank | ブランク
block | ブロック
bold | ボールド
build | ビルド
building block | 機能要素
cache | キャッシュ
callout | コールアウト
catalyst | カタリスト
Catalyst license | カタリストライセンス
collapse | 折りたたむ
Commercial license | 商用ライセンス
Community plugin | コミュニティプラグイン
Components | コンポーネント
connection | コネクション
converter | コンバーター
current file | 現在のファイル
current note | 現在のノート
custom | カスタム
Data loss | データ損失
Default | デフォルト
delete | 削除
document(s) | ドキュメント
documentation | ドキュメント または ドキュメンテーション(資料作成という意味合いの場合のみ)
E-mail address | Eメールアドレス
edit mode | 編集モード
editing mode | 編集モード
editing view | 編集ビュー
editor | エディタ
encryption password | 暗号化パスワード
end-to-end encryption | エンドツーエンド暗号化
expand | 展開
external link | 外部リンク
extract | 抽出
feature | 機能
first-class citizens | 第一級市民 (第一級クラスオブジェクトではなく比喩の方をそのまま採用)
fixer | フィクサー
fold | フォールド
Folder | フォルダ
format | フォーマット
frontmatter | フロントマター
global command | グローバルコマンド
graph | グラフ
heading | 見出し
highlight | ハイライト
hover | ホバー
ID | ID
image file | 画像ファイル
indent | インデント
indexing | インデックスを作成
indicator | インジケータ
Insider builds | インサイダービルド
interface | インターフェース
internal link | 内部リンク
italic | イタリック
JavaScript flavor | JavaScriptフレーバーの
konwledge base | ナレッジベース
Landscape | 横向き
link | リンク
linked mention | リンクされたメンション
local vault | ローカル保管庫
markdown | マークダウン
match-case | 大文字/小文字を区別
merge | 統合
Metadata | メタデータ
none | なし
note | ノート
note-taking | ノートテイキング
Obsidian | Obsidian (常に大文字から始める)
Obsidian Publish | Obsidian Publish (サービス名のためそのまま)
Obsidian Sync | Obsidian Sync (サービス名のためそのまま)
Obsidian Unlimited | Obsidian Unlimited (PublishやSync同様そのまま)
obsidian URI | Obsidian URI (大文字から始める)
OFF | オフ
ON | オン
ordered list | 順序付きリスト
outgoing link | アウトゴーイングリンク
page preview | ページプレビュー
palette | パレット
pane | ペイン
Pane layout | ペインレイアウト
pin | ピン
pinned command | ピン留めされたコマンド
plain text | プレーンテキスト
plugin | プラグイン
preview | プレビュー
preview mode | プレビューモード
provider | プロバイダー
publish change | 変更の公開
quick switcher | クイックスイッチャー
Reading experience | リーディングエクスペリエンス
reading view | リーディングビュー
regex | Regex
remote vault | リモート保管庫
Right-to-left | 右横書き
sandbox vault | サンドボックス保管庫
search | 検索
second brain | 第二の脳
Security | セキュリティ
selective sync | 選択的同期
sidebar | サイドバー
site | サイト
snippet | スニペット
starred pane | スターペイン
supporter | サポーター
tag | タグ
Third-party plugin | サードパーティプラグイン
today's note | 今日のデイリーノート
toggle | トグル、切り替える(コマンド名においてはトグルを優先的に使う)
unlinked mentions | リンクされていないメンション
unordered list | 順序なしリスト
untitled | 無題の~ (無題のファイル・無題のフォルダ)
vault | 保管庫
version history | バージョン履歴
video file | 動画ファイル
VIP | VIP
wikilink | ウィキリンク

### 同一表現の使いまわし

|Original expression|Japanese translation|
|-|-|
don't ask again | 次からは確認しない
Enter to create | Enterキーで作成
Not created yet, select to created | まだ作成されていません、作成するには選択してください
something went wrong | エラーが発生しました
Template file location | テンプレートファイルの場所

### プラグインの名称

|Plugin name|Japanese translation|
|-|-|
Audio recorder | オーディオレコーダー
Command palette | コマンドパレット
Daily notes | デイリーノート
File explorer | ファイルエクスプローラ
File recovery | ファイルリカバリー
Graph view | グラフビュー
Markdown format importer | Markdownフォーマットインポーター
Note composer | ノートコンポーザー
Open in default app | デフォルトアプリで開く
Outline | アウトライン
Page preview | ページプレビュー
Publish | パブリッシュ (Obsidian Publishはサービス名なのでそのまま)
Quick switcher | クイックスイッチャー
Random note | ランダムノート
Search | 検索
Slides | スライド
Starred notes | スター
Sync | 同期
Tag pane | タグペイン
Templates | テンプレート
Word count | ワードカウント
Workspaces | ワークスペース
Zettelkasten prefixer | Zettelkastenプレフィクサー

|Controversial term|Japanese translation|
|-|-|
議論となる用語や気になる用語 | 用語の候補などをあげるか空白にしてください|

## 日本語翻訳のルールとスタイルガイド
ヘルプドキュメントとUIの翻訳の際に採用しているルールの一覧を載せています(このドキュメント自体にも同一のルールを適用しています)。ここに記載されていない細かいルールなどについて困った場合には[JTF(日本翻訳連盟)](https://www.jtf.jp/tips/styleguide)の翻訳スタイルガイドなどを参考にしてみてください。

- スタイル全体
    - コマンド名: コマンドパレットでの検索で引っかかりやすいように単語(特に目的語)を組み合わせて表現に一貫性を持たせる(例: 新規ノートの作成、ペインを縦に分割)。
    - 日本語表現: 日本語の分かりやすさと読みやすさを心がける。
- 漢字とひらがなについて
    - 常用外漢字を使用しない。
- 全角文字と半角文字について
    - 句読点には全角の `。` と `、` を使用する。
    - 強調記号は半角 `!` ではなく全角 `！` を利用する。和文ではなるべく強調を使わないように翻訳する。`?` についても同様になるべく使わないように翻訳し、使用する場合には半角ではなく全角の `？` を使用する。見出しで使われている場合には利用する。
    - 英数字と記号は基本的に半角文字を使用する。
    - アンパサンドは全角文字 `＆` を使用し、慣習的に｢アンド｣で結ぶ単語の組み合わせに利用する(例: ドラッグ＆ドロップ、コピー＆ペースト)。
    - ｢第二の脳｣や｢第一の働き｣などの強調的表現や慣習的に漢字と組み合わせる数字表現には漢数字を使用する。
    - ｢一つは｣などの数量表現には漢数字を使用する。
    - 日付や日数などの数字には算用数字を使用する。
    - 半角数字の前後にスペースは入れない(例: 半角スペース4文字分)。
    - 半角文字と全角文字の間にスペースは入れない(例: カスタムURIプロトコル)。
    - かぎ括弧`｢｣`、丸括弧`()`、大括弧`[]`には半角文字を使用する。
    - 中黒には全角文字`・`を使用する。
- 約物について
    - 原文: `...` → 日本語: `…` に統一する(例: フォルダを入力…)。
- インデントについて
    - 半角スペース4文字分をインデントとする。
- 記号によって囲まれた単語について
    - 丸括弧 `( )` について
        - (括弧)の前後にスペースは入れない。
        - 文末に来る場合には括弧の外に句点を付ける(このようにする)。
    - 二重引用符 `" "` について
        - オプションやメニューの項目や設定は必ず｢｣で囲む(文字列が英語でも囲む)。
            - `｢設定｣ → ｢外観｣` などのオプションやボタンの遷移を表す矢印と括弧の間には半角スペースをいれる。
        - ファイル名(例: "Roam-Export-xxxxxxxxxxxxx.zip" など)、文字列パターン(例: "YYYY-MM-DD", "202001010000" など)の場合にはそのまま二重引用符で囲む。
        - 二重引用符を使用する場合にはバッククォートと同様のルールを適用する。
        - "vault/folder" 等のディレクトリの表示はそのままにする。
        - 説明に使用する英単語は｢｣で囲む(例: エイリアスの項目ででてくる｢AI｣は｢Artificial intelligence｣の略)。
        - 強調表現としての二重引用符の利用はボールドで代替する(例: ｢If Obsidian Sync "wins" the race｣ → ｢Obsidian Syncが競合に**勝る**場合｣)。
    - ハイライト `== ==` やボールド `** **` などの装飾部分については実際に日本語で利用する場面に即して、囲む部分の前後には半角スペースを入れない(例: これは==ハイライト==です)。
    - バッククォート ``` ` ` ``` について
        - ``` ` ` ``` の前後で単語が連続する場合には半角スペースをいれる。
        - 文末に来る場合には `後に半角スペースを入れない`。
        - 句読点や括弧の前後では半角スペースを入れない(例: ｢~で、`単語`、~です。`単語`｣)。
        - ``(`Shift+|`)``: これはこのままにする。
        - ホットキーやショートカットキーは `Ctrl+Shift+I` や `Ctrl/Cmd+P` のようにキーの間にスペースを入れずに `+` でつなぐ。
        - `Ctrl` や `Cmd` などの特殊キーは頭文字を大文字にし、アルファベット単体のキーは `Ctrl/Cmd+P` のように大文字にする。
        - `Ctrl/Cmd` の並び順は統一する。
        - 矢印キーは `Left arrow` などと記述する。
- 他の記号について
    - コロン `:` について
        - 例: `ノート: これは説明です`。`:` の後にのみ半角スペースを挿入する。
        - `名詞: 説明` という原文の形のままにする。
        - 文になっている場合にはなるべく読点で終わらせる。
        - `名詞: 列挙` の形の時はコロンの後の名詞はカンマで繋ぎ、ピリオドを打たない(例: `png`, `jpg`, `jpeg`, `gif`, `bmp`, `svg`)。
    - 矢印記号について
        - 半角の `←, ↓, ↑, →` を利用し、矢印の前後に半角スペースを挿入する。
- 訳語の統一
    - 上の語彙対応表に従ってすべての用語を統一表記する(インターフェースとヘルプドキュメントの両方において一貫した表現を行う)。
    - 漢字とひらがなの表記ゆれについて
        - ｢全て｣ → ｢すべて｣に統一する。
        - ｢下さい｣ → ｢ください｣に統一する。
        - ｢既に｣ → ｢すでに｣に統一する。
        - ｢極めて｣ → ｢きわめて｣に統一する。
        - ｢new, newly(新しい、新しく)｣ → ｢新規｣に不自然でない限り統一する(例: 新規作成、新規ノート)。
- 特殊な表現
    - バージョンには先頭に｢v｣と付ける(例: v0.11.1)。
    - タグの前後には半角スペースをいれる(例: #タグ )。
    - サービス名などはそのままにする(例: Obsidian Unlimited)
    - 月表現は1ヶ月、3ヶ月などとする。
- 文章
    - 長い英文でもなるべく文を短く完結にする。
    - 同じ助詞の連続をなるべく避ける。
- UI(ユーザーインターフェース用のja.jsonファイル)
    - ボックス幅が大きくなりすぎないように短く簡潔な表現にする。
    - `label-`: ウィンドウの上に表示されるラベル。
        - ｢リモート保管庫の作成｣のように助詞｢の｣によって接続して体言止めにして読点を入れない。
    - `msg-`: 通知されるメッセージ。
        - ｢~できません。｣、｢~してください。｣、｢~に成功しました。｣などの表現に統一する。
        - `…` 以外の文は句点で終わるようにする。
        - 進行中のタスクの表現は｢~中｣ではなく、｢~しています｣で終わるようにする。
    - `tootip-`: ボタンにホバーすると表示される。
        - 単語表現や幅を意識した短い表現にする。
    - `option- -placeholder`: 入力欄に表示されるプレースホルダー。
        - UIのボックス幅に入り切る短い表現にする。
    - `-desc`, `desc-`: オプション等の説明文。
        - ｢~ます。｣などの文末表現にする。


