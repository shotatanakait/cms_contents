---
Keywords: rsync, Linux, コマンド, shell, bash, zsh
Copyright: (C) 2023 Shota Tanaka
---

# rsync

`rsync`コマンドのオプションや使い方についてしらべてみました。

## 参考サイト
`rsync`コマンドに関して、わかりやすいQiitaの記事がありましたので以下に引用します。

[https://qiita.com/bezeklik/items/22e791df7187958d76c1](https://qiita.com/bezeklik/items/22e791df7187958d76c1)

## man
また、念の為`man`コマンドも読んでみました。以下はその一部を引用したものです。
> The files are transferred in archive mode, which ensures that symbolic links, devices, attributes, permissions, ownerships, etc. are preserved in the transfer.

## まとめ

- `rsync`コマンドは、`-a`オプションを用いることで、そのファイルのシンボリックリンク、デバイス、属性、パーミッション、所有権等を含めて同期することができる。
- 以下のオプションを付与して使用することが多そう。（感想）

```bash
rsync -av "$from" "$to"
```

以上です。
