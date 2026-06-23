# /loop プロンプト集 LP

Claude Code / Codex の `/loop`（定期実行・セルフペース実行）で使える日本語プロンプトのライブラリLP。単一HTMLで完結。

## 構成（3ページ・タブ切替）

1. **プロンプト集** — 19本のループ用プロンプト。キーワード検索＋「業種(6)×用途(6)」フィルタ。各カードはワンクリックでプロンプトをコピー。
2. **AGENTS / CLAUDE** — そのまま貼って使える `CLAUDE.md` / `AGENTS.md` 構造ファイル（ゴール・1ターンの粒度・ガードレール・停止条件つき）。ファイル切替＋コピー対応。
3. **復習資料** — セミナースライド（https://fuuuuuuma.github.io/ai-loop-seminar-slides/）への導線＋iframe埋め込み。

## デザイン

- 参考: forwardfuture.ai の Loop Library（loop単位カード＋ワンクリックコピー＋カテゴリ絞り込み）
- テーマ掛け合わせ: **Kawaru（ネイビー×ブルー＝信頼の基調）× ClaudeCode（コーラル＋丸ゴシック＝親しみの差し色）**
- 2軸フィルタを色で区別: 業種＝ネイビー / 用途＝コーラル
- ロゴ（ClaudeCode犬アイコン）は base64 内蔵＝単体HTMLでパス切れなし

## 公開・閲覧

- ローカル: `python3 -m http.server` でこのディレクトリを配信し `index.html` を開く
- GitHub Pages 等にこのフォルダを置けばそのまま公開可能（外部依存はGoogle Fonts／復習スライドのみ）
