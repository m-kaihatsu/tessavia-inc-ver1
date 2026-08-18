# Tessavia Corporate Website — Final Release

## Pages
- `index.html` — コーポレートTOP
- `download.html` — サービス資料請求
- `recruit.html` — 採用ページ（経理BPOスタッフ）
- `privacy.html` — プライバシーポリシー
- `404.html` — 404ページ

## SEO
- canonical / OGP
- Organization structured data
- `robots.txt`
- `sitemap.xml`

## Before production launch
1. お問い合わせフォームの送信先を接続
2. 資料請求フォームの送信先・PDF自動送付を接続
3. 採用条件（給与・勤務地・雇用形態等）を確定
4. GA4 / Search Console 等を必要に応じて設定
5. OGP画像を用意する場合は各ページの `og:image` を追加

Static HTMLなので、GitHub Pages / Cloudflare Pages / Netlify / Vercel等へそのまま配置できます。
