Title: 最初の投稿
Date: 2019-05-29
Category: テスト
Tags: テスト, 投稿
Slug: FirstPost
Authors: sassea34
Summary: 簡単にブログ作成

# How to use pelican

1. Previous settings.
    1. `git init` to initialize git repository.
    1. `git remote add origin https://github.com/sassea34/sassea34.github.io.git`
    1. Get `pmake.cmd` for windows to do `pmake html` instead of `make html`. 
        * [Pelicanでブログ作成 on Windows](https://qiita.com/daiki7nohe/items/ed82af5b302c83ff3336)

1. Upload html.
    1. `pmake html` to make html from .md files in content folder.
    2. `ghp-import output` to specify folder to publish.
    3. `git add --all`
    4. `git commit -m "(comment)"`
    5. `git push https://github.com/sassea34/sassea34.github.io.git gh-pages:master`
        * error
    6. `git fetch && git merge origin/master`

