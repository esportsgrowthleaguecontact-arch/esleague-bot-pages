# esleague-bot-pages

eS-League Bot の案内ページ（GitHub Pages 公開用リポジトリ）。

## 構成

| ファイル | 内容 |
|---|---|
| `index.html` | 案内ページ本体（単一ファイル、外部CSS/JSなし）。タイトル「eS-League Bot」、副題「リーグBot管理画面 ― 共有・閲覧版」。 |
| `tutorial.pdf` | チュートリアル「eS-League Bot チュートリアル」（9ページのPDF）。別途用意してリポジトリ直下に置く。`index.html` のチュートリアル欄からリンク済み。 |

## 公開方法（GitHub Pages）

- 公開元：`main` ブランチのルート。
- 公開URL：`https://esportsgrowthleaguecontact-arch.github.io/esleague-bot-pages/`
- リポジトリの設定 → Pages → Build and deployment の Source を「Deploy from a branch」、Branch を「main」「/(root)」にして保存する。初回のみ設定が必要。
- 以後は `index.html` を差し替えて push するだけで更新される。

## 更新手順

1. `index.html` を編集する。
2. 内容を確認する（リンク切れがないこと、実在のURLだけを使うこと、認証情報を含まないこと）。
3. `main` ブランチへ push する。数分で公開ページに反映される。

## 注意

- ページに載せるリンクは実在のものだけにする（ポータル https://es-league.games/ 、リーグ公式サイト https://growthleague.wordpress.com/ ）。推測のURLは作らない。
- 認証情報（パスワード、トークン、APIキー等）をリポジトリに入れない。
- 未実装の機能を実装済みのように書かない。準備中のものは「準備中」と明記する。
