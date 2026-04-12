# 新月通信係 / Calibration Tower

事業紹介サイト。GitHub Pages で公開。

## 構成

```
shingetsu-tsushin/
├── index.html                    # サイト本体（単一HTML）
└── .github/workflows/pages.yml   # GitHub Pages 自動デプロイ
```

## デプロイ

`main` ブランチへの push で GitHub Actions が自動実行 → GitHub Pages に反映。

## セットアップ

1. GitHub で `shingetsu-tsushin` リポジトリを作成（ライセンス: None）
2. このディレクトリの内容を push
3. Settings → Pages → Source を「GitHub Actions」に設定
4. Actions タブでデプロイ完了を確認

## 今後

Jekyll 化する場合は `_config.yml` + `_posts/` を追加し、workflow を Jekyll ビルドに差し替え。
