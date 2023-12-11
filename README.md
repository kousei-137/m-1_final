# M-1グランプリ決勝ネタ採点アプリ
※12/24にアプリを公開します。

## 開発環境
| カテゴリー | 技術スタック |
| ---- | ---- |
| フロントエンド | Nuxt.js, TypeScript, Tailwind CSS, daisyUI, Zod |
| バックエンド | Nuxt.js, TypeScript, Prisma, Sidebase, bcrypt |
| DB | MongoDB |
| インフラ | Vercel |

## 準々決勝採点アプリからの修正
※準々決勝ネタ採点アプリのGithubURL: https://github.com/kousei-137/m-1_quaterfinal
### Twitterログイン
準々決勝のアプリでは、多数のユーザーに閲覧していただいたが、ユーザー登録して実際に採点機能を利用してくれた方は閲覧した方の10%程度であった。
準々決勝のアプリではTwitter OAuth1.0を使用していたため、ログインするにはTwitterIDとパスワードを入力する手間がユーザー登録の障壁であったと考えた。
今回の決勝ネタ採点アプリでは、Twitter OAuth2.0を使用し、ユーザー登録しやすいアプリへと修正した。