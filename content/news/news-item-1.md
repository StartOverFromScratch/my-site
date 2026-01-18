+++
date = '2025-01-01T20:16:42+09:00'
draft = false
title = 'News Item 1'
reporters = ["author2"]
tags= ["topic-n"]
+++
# aaa


# ここが“色付けの本体”

1. 記事ページで「このページの記者スラッグ」を決めて、**tags** セクションにクラスを付ける

ファイル: layouts/_default/single.html
役割: 記者スラッグ（例: author2）を導出して、tags セクションに rep-<slug> クラスを付与