# react-gh-pages-sample

create-react-app で作成

```sh
npx create-react-app sample-app --template typescript
```

githubにpush

gh-pages をinstall

```sh
yarn add -D gh-pages
```

package.jsonを修正
homepage を追加
(これがないと生成されるhtmlから見たときのパスがおかしくなり動かない)

deploy

```sh
yarn build && gh-pages -d build
```

これでよしなにやってくれる
