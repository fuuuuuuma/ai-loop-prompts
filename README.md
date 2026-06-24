# /loop プロンプト集 LP

Claude Code / Codex の `/loop`（定期実行・セルフペース実行）で使える日本語プロンプトのライブラリLP。単一HTMLで完結。

## 構成（3ページ・タブ切替）

1. **プロンプト集** — ループ用プロンプト**100選**。キーワード検索＋「業種(6)×用途(6)」フィルタ。各カードはワンクリックでコピー。`/loop` の間隔は `5m`/`1h`/`1d` などCLI構文に正規化済み。
2. **AGENTS / CLAUDE** — **公式ベストプラクティス準拠**の `CLAUDE.md`（Anthropic memory ガイド）/ `AGENTS.md`（agents.md 標準）雛形。さらに下部に、設定ファイルを点検・修復する **md-doctor スキル**と、それを定期実行する **週次ルーチン（/loop）** を収録。すべてコピー対応。
3. **学習ロードマップ** — [Learn Claude Code](https://learn.shareai.run/ja/) を土台にした**日本語強化版**。AIエージェントを 0→1 で組む20ステップ（s01–s20）を5つのアーキテクチャ層に色分けして解説。`/loop` の正体である s14（ハーネスによる定期実行）を強調。
4. **復習資料** — セミナースライド（https://fuuuuuuma.github.io/ai-loop-seminar-slides/）への導線＋16:9 iframe埋め込み。

## デザイン

- 参考: forwardfuture.ai の Loop Library（loop単位カード＋ワンクリックコピー＋カテゴリ絞り込み）
- テーマ掛け合わせ: **Kawaru（ネイビー×ブルー＝信頼の基調）× ClaudeCode（コーラル＋丸ゴシック＝親しみの差し色）**
- 2軸フィルタを色で区別: 業種＝ネイビー / 用途＝コーラル
- ロゴ（ClaudeCode犬アイコン）は base64 内蔵＝単体HTMLでパス切れなし

## 公開・閲覧

- ローカル: `python3 -m http.server` でこのディレクトリを配信し `index.html` を開く
- GitHub Pages 等にこのフォルダを置けばそのまま公開可能（外部依存はGoogle Fonts／復習スライドのみ）
