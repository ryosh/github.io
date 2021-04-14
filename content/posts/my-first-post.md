---
title: "Hugoの使い方のメモ"
date: 2021-04-14T07:02:09+09:00
draft: false
tags: [ hugo ]
categories: [ blog ]
---


ローカルサーバーの起動
```
hugo server -D
```

記事の作成
```
hugo new posts/my-first-post.md
```

ローカルサーバー起動中に、`hugo new posts/xxx`を実行すると、このエラーになる。
```
Error: Unable to locate config file or config directory. Perhaps you need to create a new site.
       Run `hugo help new` for details.
```

HTMLの作成。
```
hugo
```

---
