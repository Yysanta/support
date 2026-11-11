# support

Yysantaが提供するアプリのサポートページとプライバシーポリシーを公開するGitHub Pagesリポジトリです。

## 公開URL

- トップ: https://yysanta.github.io/support/
- みんなの作戦ボード: https://yysanta.github.io/support/minnanosakusenboard/
- NudgeGoo: https://yysanta.github.io/support/nudgegoo/
- はなまるすうどく: https://yysanta.github.io/support/hanamarusudoku/
- はなまるすうどくのプライバシーポリシー: https://yysanta.github.io/support/hanamarusudoku/privacy/

## 構成

```text
assets/                         共通スタイル・画像
minnanosakusenboard/            みんなの作戦ボード
  privacy/                      プライバシーポリシー
nudgegoo/                       NudgeGooサポート
  privacy/                      プライバシーポリシー
hanamarusudoku/                 はなまるすうどく（4言語のサポート情報）
  privacy/                      プライバシーポリシー（日本語・英語・中国語・韓国語）
```

GitHub Pagesは`main`ブランチのリポジトリルートから公開します。

## 共通の規約・課金案内

- 共通利用規約: https://yysanta.github.io/support/terms/
- 購入・解約・返金: https://yysanta.github.io/support/purchases/
- 特商法表記の確認用ページ: [legal/index.html](legal/index.html)
- 特商法表記の公開前チェック: [docs/tokushoho-draft.md](docs/tokushoho-draft.md)

規約の初回公開前に、運営者・適用開始日・既存利用者への案内方法と、既存のApp Store EULAの設定・整合を確認してください。初回の適用は、本サイトへの掲載だけで全既存利用者が同意したとは扱わず、必要なアプリ内案内・同意を整えてください。適用開始日を確定し、規約のレビュー用表記を置き換えてください。購入案内のレビュー用表記も公開前に外してください。

### アプリ内で追加するリンク

各アプリの設定・ヘルプと購入画面に、共通利用規約、当該アプリのプライバシーポリシー、購入・解約・返金案内へのリンクを追加します。このリポジトリの変更はWebページのみで、アプリ本体・App Store Connectの変更は含みません。

### 新しいアプリを追加するとき

1. 共通規約が機能に合うか確認し、対象アプリ一覧を更新。
2. アプリ固有のプライバシーポリシーと、購入対象・課金方式・復元方法の説明を用意。
3. 日本語・英語のサポート／プライバシーページに共通ページへのリンクを追加。共通本文は現在日本語のみなので英語ページでは日本語である旨を明示。
4. サブスク導入時は購入前に対象機能、料金・契約期間、自動更新、体験終了後の料金、更新停止方法・期限と利用終了時期を表示。Sandboxで購入・復元・更新・失効を確認。
5. App Store Connectで必要な規約・プライバシーURL等を設定。独自EULAを採用する場合はAppleの要件との整合を別途確認。
6. 法定表示と商品案内を更新し、リンクの到達先を確認。

ハカル図（Hakaruzu）は現在プライバシーポリシーのみ掲載しており、今回の規約の適用対象には含めていません。対象に加える際は、計測機能・購入条件と規約の整合を確認してからリンクを追加してください。
