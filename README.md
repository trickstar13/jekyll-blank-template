# Jekyllブランクテンプレート
Jekyll 4.0用 非公式ブランクテンプレート  
Jekyll公式サイト: [https://jekyllrb.com/](https://jekyllrb.com/)

## 開発環境ファイルを参照してのserve
JEKYLL_ENV=development bundle exec jekyll serve --config "_config.yml,_config_dev.yml" --watch

## 本番環境にアップロードするためのbuild
JEKYLL_ENV=production bundle exec jekyll build --watch
