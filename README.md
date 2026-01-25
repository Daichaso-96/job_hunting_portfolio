Portfolio
佐藤大地 - エンジニアポートフォリオサイト
Daichi Sato – Engineer Portfolio
📌 概要 / Overview
このポートフォリオは、職業訓練校での課題をもとに作成したWebサイトです。現在就職活動用として使用しています。
This portfolio was created based on a vocational training school assignment and is currently being used for job hunting purposes.
🔗 デモサイト / Demo Site:
https://yourusername.github.io/portfolio
(リンクは公開後に更新してください / Please update the link after publishing)

🎯 目的 / Purpose

Webプログラミングスキルの習得と実践
職務経歴・スキル・資格の視覚的な提示
GitHubを活用したポートフォリオの公開


🛠️ 使用技術 / Technologies

HTML5 - セマンティックマークアップ
CSS3 - レスポンシブデザイン、グラデーション、アニメーション
JavaScript - スクロールアニメーション、DOM操作
GitHub Pages - ホスティング


📂 ファイル構成 / File Structure
portfolio/
├── index.html              # メインHTMLファイル
├── css/
│   └── style_portfolio.css # スタイルシート
├── js/
│   └── script.js          # JavaScriptファイル
├── images/
│   └── account_photo.JPG  # プロフィール画像
├── README.md              # このファイル
└── LICENSE                # ライセンス情報

✨ 主な機能 / Features
1. レスポンシブデザイン

PC、タブレット、スマートフォンに対応
768px以下でモバイル表示に切り替え

2. スムーススクロール

ナビゲーションメニューからのページ内遷移
スクロール連動のフェードインアニメーション

3. インタラクティブUI

スキルレベルの星評価アニメーション
ホバーエフェクト付きカード
タイムライン形式の職務経歴表示

4. GitHubリンク

ヘッダーとフッターにGitHubプロフィールへのリンク
アイコンの回転アニメーション


🤖 AI生成コードについて / About AI-Generated Code
このプロジェクトの一部のコードは、Anthropic社のAIモデル Claude Opus 4.5 を使用して生成されています。
Parts of this project's code were generated using Claude Opus 4.5 by Anthropic.
生成情報 / Generation Details
項目内容生成ツール / ToolClaude Opus 4.5生成日 / Date2026-01-25プロンプト概要 / Prompt試作として作成したファイルに対し、内容の変更・修正を行う
AI生成部分のファイル一覧 / AI-Generated Files
以下のファイルにAI生成コードが含まれています：

index.html - HTML構造とコンテンツ
css/style_portfolio.css - スタイル定義
js/script.js - アニメーションとインタラクション

⚠️ 注意事項 / Disclaimer

AI生成コードには誤りや脆弱性が含まれる可能性があります。
AI-generated code may contain errors or security vulnerabilities.
必ず人間によるレビューとテストを行ってください。
Please ensure thorough human review and testing before use.
本コードは参考目的であり、利用は自己責任でお願いします。
This code is provided for reference purposes only; use at your own risk.


🚀 セットアップ / Setup
1. リポジトリのクローン / Clone the Repository
bashgit clone https://github.com/yourusername/portfolio.git
cd portfolio
2. ローカルで表示 / View Locally
ブラウザで index.html を開くか、ローカルサーバーを起動してください。
Open index.html in your browser or start a local server:
bash# Python 3の場合
python -m http.server 8000

# Node.jsの場合（http-serverをインストール済み）
npx http-server
ブラウザで http://localhost:8000 にアクセスしてください。
3. GitHub Pagesで公開 / Publish with GitHub Pages

GitHubリポジトリの Settings に移動
Pages セクションを開く
Source を main ブランチに設定
Save をクリック
数分後、公開URLが表示されます


📝 カスタマイズ / Customization
個人情報の変更
index.html の以下の箇所を編集してください：
html<!-- プロフィール情報 -->
<div class="name">佐藤 大地</div>
<div>📍 栃木県宇都宮市</div>
<div>✉️ your-email@example.com</div>
<div>📱 XXX-XXXX-XXXX</div>

<!-- GitHubリンク（2箇所） -->
<a href="https://github.com/yourusername" ...>
スキルレベルの調整
index.html のスキル項目で data-skill-level を変更：
html<div class="skill-item" data-skill-level="3">
  <span class="skill-name">・HTML5/CSS</span>
  <span class="skill-stars"></span>
</div>
レベル： 1〜5（星の数に対応）
色のカスタマイズ
css/style_portfolio.css で以下の変数を変更：
css/* メインカラー（紫系グラデーション） */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* セクション番号の色 */
background: #ff6b6b;

/* 星の色 */
color: #ffd700;

📄 ライセンス / License
このプロジェクトは MITライセンス に従います。
詳細は LICENSE ファイルをご確認ください。
This project is licensed under the MIT License.
See the LICENSE file for details.

👤 作者 / Author
佐藤 大地 (Daichi Sato)

GitHub: @yourusername
Email: your-email@example.com
所属 / Affiliation: SHINBIデザインスクール Webプログラミング科


🙏 謝辞 / Acknowledgments

Anthropic Claude Opus 4.5 - コード生成支援
SHINBIデザインスクール - 学習環境の提供
GitHub Pages - ホスティングサービス


📌 注意 / Notes
ダミーコンテンツについて
このポートフォリオには、学習目的で作成された以下のダミーコンテンツが含まれています：

一部のリンク先URL
サンプル画像
テスト用テキスト

公開前に実際の情報に置き換えてください。
Regarding Dummy Content
This portfolio contains the following dummy content created for learning purposes:

最終更新日 / Last Updated: 2026-01-25
