# CLAUDE.md — portfolio

卒論を掲載するシンプルなポートフォリオサイト（静的 HTML/CSS、GitHub Pages）。

> ⚠️ **このリポは public**。実名・メールアドレス・非公開リポ名等を file 本文 / commit message に書かない（claude-config CLAUDE.md §安全規則）。サイト本文・卒論 PDF に何を載せるかはユーザーの判断で、Claude が勝手に個人情報を追加しない。

共通規約は `~/Claude/CONVENTIONS.md`（claude-config）。作業開始時は `git fetch` → 本ファイル → SESSION.md の順に読む。

## 構成

| ファイル | 役割 |
|---|---|
| `index.html` / `style.css` | サイト本体（フレームワークなし） |
| `thesis.pdf` | 掲載している卒論 |
| `.claude/launch.json` | ローカルプレビュー設定（python3 http.server, port 8080） |

## URL・デプロイ

- サイト: https://natsunooda.github.io/portfolio/
- デプロイ: main に push すると GitHub Pages が自動反映（ビルド工程なし）
- ローカル確認: `python3 -m http.server 8080` をリポ root で実行
