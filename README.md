# MyVueSplash

ポートフォリオ

### 参考にしたページ

https://www.hypertextcandy.com/vue-laravel-tutorial-introduction

#### このリポジトリで勉強したこと

- Vue.js と Laravel を組み合わせて SPA を構築する方法

- Laravel

  - 写真一覧収得 API
  - ユーザー登録 API
  - ログイン API
  - ログアウト API
  - 写真投稿 API
  - 写真詳細ページ API
  - CSRF 対策
  - 写真削除 API（追加機能）
  - コメント API(作成中)
  - いいね API(作成中)
  - マイページ API（作成中）

- Vue

  - VueRouter
  - Vuex

    - store を用いた状態管理

      - state の表示
      - getters の表示
      - state の更新履歴の表示
      - state 更新履歴の特定時点に状態を戻す

- Docker での開発環境構築

  - コマンド
    - Docker 起動 : docker-compose up -d
    - サーバー立ち上げ : php artisan serve --host 0.0.0.0 --port 8081

- node.js(フロントエンドのビルド)

  - コマンド
    - npm run watch : 一度コンパイルが走った後に監視モードに入り、ファイルの変更があるたびに自動的に再度コンパイルが実行

* AWS S3 を用いた写真アップロード保管
