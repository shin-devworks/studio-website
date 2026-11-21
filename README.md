# MIOTSUGI 公式サイト（初期版）

Cloudflare Pages向けの静的HTMLサイトです。公開環境の動作確認を目的とした初期版であり、App Store審査用の法的文書は未完成です。

## 構成

- `/` ブランドトップ
- `/games/hajo-senki/` ゲーム紹介
- `/privacy/hajo-senki/` プライバシー（監査待ち）
- `/terms/hajo-senki/` 利用規約（確認待ち）
- `/support/` サポート（窓口設定待ち）

## Cloudflare Pages

GitHubへこのディレクトリのファイルをpushし、Cloudflare Pagesの「Import an existing Git repository」で対象リポジトリを選択します。Framework preset: None、Build command: 空欄（または `exit 0` が必要なUIならそれを指定）、Build output directory: `/`（リポジトリのルート、UIによっては空欄または`.`）。

## 公開前の必須確認

- プライバシーポリシー：Flutterコード監査後に確定
- 利用規約：GPS、セーブ、課金などの記述を最終確認
- サポート：有効な問い合わせ方法を用意して送受信を確認
- スクリーンショット・PV：正式素材のみ掲載
- YouTube・App Storeリンク：正式URLが確定後に追加
- 独自ドメイン：任意、後日接続可能
- GitHubへAPIキー、アカウント情報、個人情報をpushしない

公開した初期版の法的文書・問い合わせページを、完成したポリシーやサポートページとしてApp Store Connectに登録しないでください。
