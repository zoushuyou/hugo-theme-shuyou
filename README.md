# hugo-theme-shuyou
It is based on [hugo-theme-cleanwhite](https://github.com/zhaohuabing/hugo-theme-cleanwhite)

## customization

I just do some customization for search.

And it can be used for my git submodule.

## usage

```bash
git submodule add https://github.com/shuyouyou/hugo-theme-shuyou.git themes/shuyou
```

## update

```bash
git submodule update --remote --merge
```

## remove

```bash
git submodule deinit -f -- themes/shuyou
rm -rf .git/modules/themes/shuyou
git rm -f themes/shuyou
```

## reference

[git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

[hugo-theme-cleanwhite](https://github.com/zhaohuabing/hugo-theme-cleanwhite)

[hugo-theme-shuyou](https://github.com/shuyouyou/hugo-theme-shuyou)