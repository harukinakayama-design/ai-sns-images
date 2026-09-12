# ai-sns-images

Threads自動投稿（画像添付版）用の画像ホスティング専用リポジトリ。

- 生成した表紙画像・本文内図解画像のみを置く。個人情報・案件情報・トークン等の機密情報は一切含めない。
- 画像を追加してpushすると、`https://raw.githubusercontent.com/harukinakayama-design/ai-sns-images/main/<パス>`が公開URLになる。このURLを`claude-project`側の`life_design/projects/stock_business/ai_sns/automation/threads/queue.json`の`image_url`に指定する。
- 運用元（本体プロジェクト）：`claude-project`リポジトリの`life_design/projects/stock_business/ai_sns/`配下。

## フォルダ構成

- `threads/YYYY-MM/` … Threads投稿用の画像をアップロード日の月別で格納
