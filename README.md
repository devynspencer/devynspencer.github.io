# Blog

This is my personal blog. It is built using [Hugo](https://gohugo.io/).

## Setup

Add the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme:

```shell
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo
git submodule update --remote --merge
```

Build the project:

```shell
hugo serve --buildDrafts
```
