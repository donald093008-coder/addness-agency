# Google検索への登録手順（本人作業）
1. website/ をこの内容で公開（Cloudflare Pagesへデプロイ）。公開後 /robots.txt と /sitemap.xml が開くことを確認
2. https://search.google.com/search-console →「URLプレフィックス」に https://kikigaki-terakoya.pages.dev/ を登録
3. 所有確認は「HTMLタグ」を選び、出たmetaタグを index.html の <head> に入れて再公開→確認
4. 「サイトマップ」に sitemap.xml を送信、「URL検査」でトップを「インデックス登録をリクエスト」
5. 数日後に「聞き書き寺子屋さん」で検索して確認
