# renai-mirai-sekkeiten

体験型展示「恋愛未来設計展」のランディングページ。
Love Analysis Project（100BANCH採択プロジェクト）主催。

## 公開URL

GitHub Pagesで公開: `https://<GitHubユーザー名>.github.io/renai-mirai-sekkeiten/`
（Settings → Pages で有効化後に確定するURLをここに追記する）

## 構成

- `index.html` — LP本体。1ファイル完結（外部フォントはGoogle Fontsのみ使用）
- `SITE_GUIDE.md` — サイトの言葉遣い・デザイントークン・事実関係のルール。
  編集する前に必ず読むこと（Claude CodeやCoworkに渡す際も、まずこのファイルを読ませる）

## 編集時の注意

- 事実（会場・日程・入場料など）は `SITE_GUIDE.md` の事実表を正とする
- 色・書体は `index.html` 内のCSS変数（`--now-*` / `--future-*`）経由でのみ変更する
- 「恋テストv2は当日会場限定」「街コン・合コンという言葉を使わない」など、
  言葉の規約は `SITE_GUIDE.md` §3を参照

## デプロイ

GitHub Pages使用。`main`ブランチの `index.html` をpushすれば自動反映される
（Settings → Pages → Source を `main` ブランチ・ルートディレクトリに設定済みの前提）。
