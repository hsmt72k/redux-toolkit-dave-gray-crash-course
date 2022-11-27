# Dave Gray's React Redux Toolkit On Crash Course

Redux ToolkitとRTK Queryを使ってModern Reduxを学ぶ、初心者向けのチュートリアルシリーズです。

<p style="color: red;">
※ 動画リンクはクリックしても別タブで開きません。
別タブで開きたい場合は、Ctrl（Command）キーを押しながらリンクをクリックしてください
</p>

React の基礎をまだ学んでいない方は、
Redux Toolkit の前に以下の動画シリーズで React の基礎をひと通り学びましょう。

React Tutorials:  
https://github.com/hsmt72k/react-basics-dave-gray-crash-course

## CHAPTERS

React Redux Toolkit Tutorial series playlist:  
https://www.youtube.com/playlist?list=PL0Zuz27SZ-6M1J5I1w2-uZx36Qp6qhjKo

CHAPTER 01. 
<a href="#start_here">
    <strong>Start Here</strong>
<a>

CHAPTER 02. 
<a href="#example_project">
    <strong>Example Project</strong>
<a>

CHAPTER 03. 
<a href="#async_thunk">
    <strong>Async Thunk</strong>
<a>

CHAPTER 04. 
<a href="#blog_project">
    <strong>Blog Project</strong>
<a>

CHAPTER 05. 
<a href="#performance">
    <strong>Performance</strong>
<a>

CHAPTER 06. 
<a href="#rtk_query">
    <strong>RTK Query</strong>
<a>

CHAPTER 07. 
<a href="#rtk_query_advanced">
    <strong>RTK Query Advanced</strong>
<a>

CHAPTER 08. 
<a href="#redux_login_jwt_auth_rtk_query">
    <strong>Redux Login JWT Auth RTK Query</strong>
<a>

<h2 id="start_here">CHAPTER 01. Start Here</h2>

<a href="https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=5">
    <img src="./images/thumbnail_01.start_here.jpg" width="240px">
</a>

[https://youtu.be/u3KlatzB7GM](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=5)

Redux Toolkit は、Reactアプリに Redux のグローバルな状態管理を実装するために推奨される方法です。
このステップバイステップのチュートリアルで、Store、Slice、Reducer、および Action について学びましょう。

[[00:29](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=29)] ようこそ   
[[00:42](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=42)] 前提知識  
[[01:11](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=71)] Redux と Redux Toolkit の比較  
[[01:42](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=102)] プロジェクトのセットアップ  
[[02:24](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=144)] Redux Toolkit のインストール  
[[02:51](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=171)] Store の作成  
[[04:07](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=247)] グローバルストアの状態をアプリに提供する  
[[05:05](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=305)] Slice を作成する  
[[08:48](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=528)] Store に Slice Reducer を追加する  
[[09:39](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=579)] コンポーネントで Action を dispatch する  
[[13:29](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=809)] App の機能チェック  
[[13:59](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=839)] Slice Action の追加作成  
[[15:32](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=932)] コンポーネントで新しい Action を適用する  
[[19:44](https://www.youtube.com/embed/u3KlatzB7GM?autoplay=1&start=1184)] 新機能の確認  

<h2 id="example_project">CHAPTER 02. Example Project</h2>

<a href="https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=5">
    <img src="./images/thumbnail_02.example_project.jpg" width="240px">
</a>

[https://youtu.be/hI-VgEaCMyQ](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=5)

このサンプルプロジェクトで Redux Toolkit を使ったアプリの構造とデータフローについてより深く学ぶことができるようになります。

[[00:15](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=15)] ようこそ   
[[00:28](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=28)] 前提知識  
[[00:45](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=45)] ドキュメントと高速化  
[[01:13](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=73)] スターターコード  
[[02:32](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=152)] posts スライスを作成する  
[[03:45](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=225)] ストアに postsReducer を追加  
[[04:30](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=270)] PostsList コンポーネントを作成  
[[05:58](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=358)] 投稿セレクタを作成  
[[07:29](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=449)] App.js に PostsList をインポートする  
[[08:34](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=514)] postAdded reducer 関数  
[[09:46](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=586)] Action creator の関数は自動的に生成される  
[[10:12](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=612)] Immer.js が createSlice でアクティブになる  
[[11:14](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=674)] AddPostForm コンポーネント   
[[13:25](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=805)] 新規投稿の保存  
[[17:08](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1028)] 状態のフォーマットを prepare コールバックに移動  
[[20:25](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1225)] Redux の Devtools  
[[22:20](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1340)] usersSlice を作成する  
[[23:36](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1416)] usersReducer をストアにインポートする  
[[24:02](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1442)] postsSlice の prepare コールバックを修正する  
[[24:30](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1470)] AddPostForm コンポーネントを修正   
[[28:57](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1737)] PostAuthor コンポーネントを作成   
[[30:28](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1828)] PostAuthor を PostsList にインポートする  
[[32:25](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1945)] date-fns 依存のインストール  
[[33:10](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=1990)] postsSlice で日付データを扱う   
[[34:55](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=2095)] TimeAgo コンポーネント   
[[36:18](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=2178)] TimeAgo を PostsList にインポートする   
[[37:29](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=2249)] 最新の投稿を最初に表示する  
[[39:02](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=2342)] postsSlice にリアクションデータを追加する   
[[41:30](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=2490)] ReactionButtons コンポーネント   
[[43:39](https://www.youtube.com/embed/hI-VgEaCMyQ?autoplay=1&start=2619)] ReactionButtons を PostsList にインポートする  

<h2 id="async_thunk">CHAPTER 03. Async Thunk</h2>

<a href="https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=5">
    <img src="./images/thumbnail_03.async_thunk.jpg" width="240px">
</a>

[https://youtu.be/93CR_yURoII](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=5)

この React Redux Thunk Middleware チュートリアルでは、Redux Toolkit の Axios を使用して
非同期アクションを作成する方法を学習します。
Thunk とは何か、そして Redux Slice の外部で非同期 Thunk を作成する方法について学びます。

[[00:15](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=15)] ようこそ   
[[00:26](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=26)] 前提知識  
[[00:43](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=43)] より速いペースで進む  
[[01:06](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=66)] Thunk とは？  
[[01:34](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=94)] 初期状態を変更する  
[[02:58](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=178)] 状態の形に合わせて調整する  
[[04:44](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=284)] fetchPosts の非同期 Thunk を作成する  
[[07:02](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=422)] extraReducers と builder ケースを追加する  
[[10:08](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=608)] fetchPosts の非同期 Thunk を dispatch する  
[[13:51](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=831)] PostsExcerpt コンポーネントの構築   
[[15:31](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=931)] ロード状態を表示する   
[[19:00](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=1140)] fetchUsers 非同期 Thunk を作成する   
[[21:50](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=1310)] アプリのロード時に fetchUsers を dispatch する  
[[23:25](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=1405)] addNewPost async thunk の作成  
[[25:39](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=1539)] addNewPost async thunk を dispatch する  
[[29:15](https://www.youtube.com/embed/93CR_yURoII?autoplay=1&start=1755)] 簡単な修正   

<h2 id="blog_project">CHAPTER 04. Blog Project</h2>

<a href="https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1?autoplay=1&start=5">
    <img src="./images/thumbnail_04.blog_project.jpg" width="240px">
</a>

[https://youtu.be/-f1iAsrkyB0](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=5)

この動画では、React と Redux を使ってブログアプリのプロジェクトを構築します。
React のブログアプリプロジェクトを使用して、Redux Toolkit での CRUD の例を提供します。
CRUD とは、Create（作成）、Read（読み取り）、Update（更新）、Delete（削除）の頭文字をつなげたワードです。
ブログの記事の作成、読み込み、更新、削除を行います。

[[00:16](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=16)] ようこそ   
[[00:29](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=29)] 前提知識  
[[00:56](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=56)] スターターコードの概要  
[[01:41](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=101)] selectPostById セレクタ  
[[03:04](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=184)] SinglePostPage コンポーネント  
[[05:06](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=306)] React Router のインストール  
[[05:54](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=354)] React Router を index.js に適用する  
[[07:28](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=448)] レイアウトコンポーネント  
[[08:38](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=518)] App.js のルーティング  
[[10:43](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=643)] SinglePostPage で useParams を使用する  
[[11:48](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=708)] PostsExcerpt コンポーネント  
[[12:54](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=774)] コードのテスト  
[[13:40](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=820)] ブログヘッダーの追加  
[[16:18](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=978)] Edit Post のリンクを追加する  
[[17:00](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1020)] EditPostForm コンポーネント  
[[21:24](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1284)] updatePost の非同期 Thunk  
[[22:38](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1358)] updatePost のビルダーケース  
[[24:46](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1486)] updatePost のディスパッチ  
[[25:13](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1513)] EditPostForm のルーティング  
[[25:58](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1558)] updatePost のテスト  
[[27:13](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1633)] deletePost 非同期 Thunk  
[[29:13](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1753)] deletePost のビルダーケース  
[[30:14](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1814)] deletePost の dispatch  
[[31:59](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1919)] AddPostForm での useNavigate  
[[32:43](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=1963)] すべての CRUD 操作のテスト  
[[34:13](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=2053)] updatePost の修正によるダミーの API テスト  
[[36:38](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=2198)] リアクション名の検証  
[[37:49](https://www.youtube.com/embed/-f1iAsrkyB0?autoplay=1&start=2269)] アプリのロード時に API の投稿データを読み込む  

<h2 id="performance">CHAPTER 05. Performance</h2>

<a href="https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=5">
    <img src="./images/thumbnail_05.performance.jpg" width="240px">
</a>

[https://youtu.be/GdOgYQzGexY](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=5)

React Redux のパフォーマンステクニックと最適化について、私たちのブログプロジェクトを見て、
コンポーネントがいつ再レンダリングされるのか、その理由を確認しながら学びます。
メモ化されたセレクタ、createEntityAdapter、そして React.memo.Redux を取り上げます。

[[00:36](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=36)] ようこそ   
[[00:50](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=50)] 前提知識  
[[01:07](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=67)] スターターコードノート  
[[01:55](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=115)] UsersList コンポーネント   
[[03:11](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=191)] selectByUserId セレクタ   
[[03:58](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=238)] UserPage コンポーネント   
[[06:00](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=360)] App.js にユーザールートを追加する  
[[06:44](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=404)] キャッチオールルートの追加  
[[07:39](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=459)] ヘッダーに Users リンクを追加する   
[[08:04](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=484)] ユーザーコンポーネントのテスト  
[[09:15](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=555)] count ステート、reducer、selector の追加  
[[11:24](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=684)] ヘッダへのカウンタの追加  
[[12:30](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=750)] 簡単なタイポの修正  
[[12:58](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=778)] 最適化の問題1  
[[15:02](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=902)] 再レンダリングの原因究明  
[[16:01](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=961)] メモ化されたセレクタの作成  
[[17:50](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1070)] UserPage コンポーネントを更新する  
[[18:56](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1136)] 変更点のテスト  
[[20:36](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1236)] 最適化の問題2  
[[21:16](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1276)] React.memo で解決する  
[[23:27](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1407)] 全機能を使った解決策  
[[23:51](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1431)] 正規化  
[[24:27](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1467)] createEntityAdapter の追加  
[[25:37](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1537)] 初期状態の変更  
[[26:17](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1577)] エンティティをルックアップオブジェクトとして利用する  
[[26:49](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1609)] エンティティアダプタの CRUD メソッドの適用  
[[28:51](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1731)] エンティティアダプタが生成するセレクタ  
[[30:33](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1833)] postsSlice の変更点の確認   
[[31:14](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1874)] PostsList コンポーネントの変更点  
[[32:17](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1937)] PostsExcerpt コンポーネントの変更   
[[33:02](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1982)] エンティティアダプタの変更点のテスト  
[[00:36](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=36)] ようこそ   
[[00:50](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=50)] 前提知識  
[[01:07](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=67)] スターターコードノート  
[[01:55](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=115)] UsersList コンポーネント   
[[03:11](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=191)] selectByUserId セレクタ   
[[03:58](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=238)] UserPage コンポーネント   
[[06:00](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=360)] App.js にユーザールートを追加する  
[[06:44](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=404)] キャッチオールルートの追加  
[[07:39](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=459)] ヘッダーに Users リンクを追加する   
[[08:04](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=484)] ユーザーコンポーネントのテスト  
[[09:15](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=555)] count ステート、reducer、selector の追加  
[[11:24](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=684)] ヘッダへのカウンタの追加  
[[12:30](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=750)] 簡単なタイポの修正  
[[12:58](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=778)] 最適化の問題1  
[[15:02](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=902)] 再レンダリングの原因究明  
[[16:01](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=961)] メモ化されたセレクタの作成  
[[17:50](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1070)] UserPage コンポーネントを更新する  
[[18:56](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1136)] 変更点のテスト  
[[20:36](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1236)] 最適化の問題2  
[[21:16](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1276)] React.memo で解決する  
[[23:27](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1407)] 全機能を使った解決策  
[[23:51](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1431)] 正規化  
[[24:27](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1467)] createEntityAdapter の追加  
[[25:37](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1537)] 初期状態の変更  
[[26:17](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1577)] エンティティをルックアップオブジェクトとして利用する  
[[26:49](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1609)] エンティティアダプタの CRUD メソッドの適用  
[[28:51](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1731)] エンティティアダプタが生成するセレクタ  
[[30:33](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1833)] postsSlice の変更点の確認   
[[31:14](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1874)] PostsList コンポーネントの変更点  
[[32:17](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1937)] PostsExcerpt コンポーネントの変更   
[[33:02](https://www.youtube.com/embed/GdOgYQzGexY?autoplay=1&start=1982)] エンティティアダプタの変更点のテスト  

<h2 id="rtk_query">CHAPTER 06. RTK Quer</h2>

<a href="https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=5">
    <img src="./images/thumbnail_06.rtk_query.jpg" width="240px">
</a>

[https://youtu.be/HyZzCHgG3AY](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=5)

この React Redux Toolkit Query チュートリアルでは、RTK Query と React を使用して CRUD サンプルアプリを構築します。
RTK Query は、あなたのコードから API ロジックを抽象化し、簡単に実装できるようにカスタム React フックを作成します。

[[00:14](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=14)] ようこそ   
[[00:28](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=28)] 前提知識  
[[00:46](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=46)] プロジェクトの依存関係  
[[01:41](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=101)] React v18 インデックス変更点  
[[02:17](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=137)] JSON サーバ  
[[03:48](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=228)] アプリと TodoList のコンポーネント  
[[05:07](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=307)] api スライスの作成  
[[08:47](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=527)] ApiProvider  
[[09:57](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=597)] TodoList で useGetTodosQuery を適用する  
[[12:30](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=750)] スライスに mutation を追加する  
[[15:21](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=921)] TodoList に mutation フックを適用する  
[[18:08](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=1088)] キャッシュされたデータ  
[[19:14](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=1154)] タグ、キャッシュの無効化、および自動リフェッチ  
[[21:48](https://www.youtube.com/embed/HyZzCHgG3AY?autoplay=1&start=1308)] レスポンスの変換  

<h2 id="rtk_query_advanced">CHAPTER 07. RTK Query Advanced</h2>

<a href="https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=5">
    <img src="./images/thumbnail_07.rtk_query_advanced.jpg" width="240px">
</a>

[https://youtu.be/9P2IUx13MZI](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=5)

この上級編の動画では、React、Redux Toolkit、および RTK Query を使用して、
ブログプロジェクトを Axios 非同期 Thunk から RTK Query、正規化ステート、楽観的更新に完全に移行させます。

[[00:34](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=34)] ようこそ   
[[00:48](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=48)] 前提知識  
[[01:05](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=65)] スターターソースコード  
[[01:46](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=106)] JSON サーバ  
[[03:50](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=230)] api スライスの作成  
[[05:43](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=343)] postSlice を拡張 api スライスに更新する  
[[08:54](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=534)] getPosts エンドポイントメソッド  
[[13:19](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=799)] postsSlice のセレクタを更新  
[[15:50](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=950)] ストアの再設定  
[[17:51](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1071)] index.js の更新  
[[18:59](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1139)] PostsList コンポーネント  
[[21:18](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1278)] PostAuthor コンポーネント  
[[22:21](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1341)] getPostsByUserId エンドポイントメソッド  
[[24:50](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1490)] addNewPost エンドポイントメソッド  
[[26:09](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1569)] updatePost エンドポイントメソッド  
[[27:13](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1633)] deletePost エンドポイントメソッド  
[[27:58](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1678)] 自動生成されたフックを出力する  
[[28:30](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1710)] AddPostForm コンポーネント  
[[30:57](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1857)] EditPostForm コンポーネント   
[[33:13](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=1993)] UserPage コンポーネント  
[[36:04](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=2164)] Header コンポーネント  
[[37:00](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=2220)] リアクションの最適化更新  
[[42:49](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=2569)] ReactionButtons コンポーネント  
[[44:57](https://www.youtube.com/embed/9P2IUx13MZI?autoplay=1&start=2697)] DevTool で Redux のステートキャッシュとネットワークリクエストを確認  

<h2 id="redux_login_jwt_auth_rtk_query">CHAPTER 08. Redux Login JWT Auth RTK Query</h2>

<a href="https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=5">
    <img src="./images/thumbnail_08.redux_login_jwt_auth_rtk_query.jpg" width="240px">
</a>

[https://youtu.be/-JJFQ9bkUbo](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=5)

JWT アクセス、リフレッシュトークン、クッキーなどを使用したReact Redux ログイン認証フローを学びます。
この動画では、JWT アクセスとリフレッシュトークン、セキュアクッキー、
RTK Query ベースのクエリ再認証ラッパーを使用した React Redux のログインと認証フローをセットアップしていきます。

[[00:46](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=46)] ようこそ  
[[01:36](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=96)] スターターコードと依存関係  
[[02:30](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=150)] Redux を始める: authSlice  
[[05:50](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=350)] ベースクエリ  
[[09:06](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=546)] ベースクエリに再認証ラッパーを加えたもの  
[[14:57](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=897)] apiSlice  
[[15:51](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=951)] apiSlice を拡張して auth にする  
[[17:27](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1047)] Redux のストアを設定する  
[[19:46](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1186)] React を始める: index.js  
[[22:33](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1353)] レイアウトコンポーネント  
[[23:28](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1408)] パブリックコンポーネント  
[[24:11](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1451)] Redux: エクスポート useLoginMutation  
[[24:54](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1494)] ログインコンポーネント  
[[31:48](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=1908)] RequireAuth コンポーネント  
[[34:33](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2073)] ウェルカムコンポーネント  
[[37:12](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2232)] App.js ルーティング  
[[40:56](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2456)] Node.js のバックエンド動作確認  
[[43:20](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2600)] ログインフローをテストする  
[[44:16](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2656)] Redux: apiSlice をユーザに拡張する  
[[47:20](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2840)] React UsersList コンポーネント  
[[49:16](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2956)] App.js のルーティングを更新  
[[49:57](https://www.youtube.com/embed/-JJFQ9bkUbo?autoplay=1&start=2997)] JWT Auth フローと RTK Query キャッシュ  
