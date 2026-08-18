# Tessavia Corporate Website

Tessavia株式会社のコーポレートサイトです。

## Files

- `index.html` — TOPページ
- `privacy.html` — プライバシーポリシー

## Deploy

静的HTMLのみで構成されています。  
GitHub Pages / Cloudflare Pages / Netlify / Vercel などの静的ホスティングへ、そのままデプロイできます。

### GitHub Pages

1. このフォルダの中身をGitHubリポジトリへpush
2. GitHubの `Settings` → `Pages`
3. `Deploy from a branch` を選択
4. `main` ブランチ / `/ (root)` を指定
5. 公開URLを確認

## Notes

- CSS・ロゴ・代表写真はHTML内に埋め込み済みのため、画像ファイルやCSSファイルの追加配置は不要です。
- お問い合わせフォームは静的サイト向けの簡易仕様です。本番運用ではフォームサービスまたはバックエンドとの接続を推奨します。
- `privacy.html` はTOPページのフッターから遷移します。
