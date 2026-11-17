# ホームページをGoogleで検索できるようにする

1. robots.txt / sitemap.xml をサイトのルート（website/ の直下）に置いて公開
2. head-snippet.html の内容を各ページの <head> に入れる（title・description・canonicalはページごとに変える）
3. Google Search Console (https://search.google.com/search-console) で「URLプレフィックス」に https://kikigaki-terakoya.pages.dev/ を登録（所有確認はHTMLタグ方式が簡単。metaタグをトップの head に足す）
4. サイトマップに sitemap.xml を送信し、「URL検査」でトップを「インデックス登録をリクエスト」
5. 数日後に「聞き書き寺子屋さん」で検索して確認
