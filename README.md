<div align="right">
  <img src="https://komarev.com/ghpvc/?username=YoshimuraKoei" />
</div>

# Hi, I'm Koei 👋
データ活用・ソフトウェア開発などに興味があります.
研究で機械学習をしており, 趣味でソフトウェア開発やワークフローでの自動化をちょっとしています.
最近エディタは cursor から neovim にゆるやかに移行していますが, わからないことだらけです. 
atcoder も最近始めました. あと Codex $100 プランに入っています.

<br>

## 最近のマイブーム・興味あること・趣味
- 朝活 × コーヒー 界隈
    - コーヒーソムリエの資格で体系的に勉強したい.
- atcoder
    - streak が切れないように毎日やっています.
- IVE (K-POP)
    - 4/18(土) の京セラライブから余韻が抜けていない. その勢いで家にスピーカーを導入した.
- 卓球
    - 友達を倒すことでうまくなってきました.
- K-POP ダンス
    - サークルを引退してからも月一回ペースぐらいで踊っていました (最近は友達と予定合わず)

<br>

## 🛠 Skills

<img alt="my skills" src="https://skillicons.dev/icons?theme=dark&perline=8&i=html,css,js,ts,react,nextjs,python,nodejs,postgresql,git,github,neovim" />

<br>

## 📊 Activities

<div align="left">
  <img alt="github stats" height="170px" src="https://github-readme-stats-sigma-five.vercel.app/api?username=YoshimuraKoei&theme=vue-dark&show_icons=true" />
  <img alt="Top Langs" height="170px" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=YoshimuraKoei&theme=vue-dark&layout=compact" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YoshimuraKoei&theme=vue-dark" alt="GitHub Streak" />
</div>

<br>

## 🚀 Projects

### User Lifelong Behavior Modeling
Taobao・KuaiRand などのデータセットを用いて推薦システムのオフライン学習の共同研究を行っています.
推薦の精度を上げるため, ユーザーの長期系列を効率的に活用する方法を探っています.
関連研究としては, ユーザーの興味に応じて動的にユーザー表現を作り替える [DIN （2019: Deep Interest Network for Click-Through Rate Prediction）](https://dl.acm.org/doi/abs/10.1145/3219819.3219823)のモデルです.

### データ解析コンペティション
（そのうち書きます）

### Blog Portfolio
Next.js App Router と Prisma / PostgreSQL を使った, ブログ兼ポートフォリオサイトです.
設計は私がしておりますが, 大部分の開発は Codex が担っています（コードは読みますが）.
現在鋭意開発中です. ボトルネックは人間で, Figma でデザインを作るところで詰まっています.
認証, 入力バリデーション, 画像アップロード, レート制限、運用ログなど, 本番運用を意識した機能も実装しています.

### AI x Remotion
（そのうち書きます）

### 社内の勤怠モバイルアプリ開発
TypeScript と ReactNative を使った Android, iOS 対応のネイティブアプリケーション開発をチームで行いました.
主にフロントエンドを担当し, Storybook を用いた UI 開発, フロントのバリデーションや勤怠ロジックなどを経験しました.
アジャイル開発の形式を取り, 2週間ごとにチームでスプリントレビューを行うのが楽しかったです.

### Codex Local Sweep
これについては小規模なのですが, 下記に記事を書きました. Mac の launchd 機能を用いて Codex に定期的なタスクを実行させる取り組みです.
Codex は特定のセッション上で, 非対話モードとして動かすことができます. そのため, 複数プロジェクトにおいて, 毎朝次のタスクを把握させることができ, 次のタスクを Slack に投稿させています.
これにより, 毎朝次に取り組むべきタスクを Slack で一元管理できるとともに, 取り組む優先順位を組むのが楽になります.
タスク管理は自身が把握しにいく push 型から, 少しずつタスク管理されにいく pull 型へと移行しつつあります.
https://zenn.dev/noeten/articles/codex-local-sweep

### 朝活 bot
完全に趣味ですが, 研究室の Slack に朝活 bot を導入しました.
「午前 8:30~9:00 の間に研究室で Slack のボタンを押すと朝活ポイントが貯まる」という仕組みにしており, 現在10名程度が z-asakatsu チャンネルに所属しています.
Slack API と GAS の完全無料技術スタック（有料プランに元から入っているのは除く）で構成されており, GAS のトリガーによって毎日 bot のメッセージが送られてきます.

### koei-clone
AI 時代になると, インターネット上に存在する数多くの文章が AI を用いて書かれたものとなりそうだなと感じました.
そこで, 「自分自身の文章をファインチューニングし, 自分自身を学習した LLM を作れないか？」と考えました.
学習データさえ蓄積すれば作れるだろう, そう思い, 
「毎日決まった時間に AI が質問を投げかけ, その問いかけに対しての返答を Supabase に蓄積させる」ことを目指したリポジトリです.
当初自分が思い描いていた MVP は実現しましたが, 

1. 問いかけに答えるのが面倒
2. 問いかけが面白くならない（多様性の欠如、質問の不明瞭性）

から, 結局今は止めてしまいました. 次なるアプローチとしては Slack の Times を学習させることを考えており, Slack の Times にデータを蓄積中です.

https://github.com/YoshimuraKoei/koei-clone
https://zenn.dev/noeten/articles/8388a63b10015d

### knowledge-RAG
学び続けていると, 学んだことをアウトプットして定着させたつもりでも忘れてしまいます. 「いつ」「どんな文脈で」「何を」学んだのか, それを明らかにしたいと思って構築した RAG のプロジェクトです.
Bot に, 「ディープラーニングってなんだっけ？」のように問いかけると、質問の答えと関連する Notion ページを返してくれるようにしました.
ですが, 最近は neovim に移行してターミナルと仲良くなり始めていて, 学びのアウトプットを Notion ではなくローカルのマークダウンファイルに書くことが多いです...
ナレッジ管理体制が固まり次第, テコ入れしていこうかなと考えています.

https://github.com/YoshimuraKoei/knowledge-RAG

### notebooklm-mcp-cli-zsh-helpers
主に業界研究・企業研究において NotebookLM が CLI で活躍してくれます. もちろん, 他の用途でも活用可能です.
既存の notebooklm-mcp-cli というツールでエイリアスを付け加えただけですが, かなり使いやすかったので布教します.
ローカルの AI エージェントのトークンを使うことがなく, ローカルに知見を溜めやすいため, 神です.

https://github.com/YoshimuraKoei/notebooklm-cli-zsh-helpers

<br>

## 🌱 Currently Learning

- ユーザー課題に基づくプロダクト開発
- データ活用・機械学習
- バックエンド設計
- クラウドデプロイ
- 生成AIを使った業務効率化

<br>

## 📫 Links

- Portfolio: Coming soon
- Zenn / Qiita: Coming soon
- LinkedIn: Coming soon
