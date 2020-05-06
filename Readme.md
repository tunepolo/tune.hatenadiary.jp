# tune.hatenadiary.jp

Source of https://tune.hatenadiary.jp

[blogsynnc](https://github.com/x-motemen/blogsync)を使ってデータを抽出している。


## blogsyncのセットアップ

```
$ brew install Songmu/tap/blogsync

$ cat ~/.config/blogsync/config.yaml

tune.hatenadiary.jp:
  username: tune
  password: <API KEY>
default:
  local_root: <EXPORT PATH>

$ blogsync pull tune.hatenadiary.jp
```

