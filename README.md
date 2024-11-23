# practice-conventional-commits


## コマンドメモ
```bash
# インストール
npm install --save-dev @commitlint/config-conventional @commitlint/cli
npm install --save-dev conventional-changelog-cli

# conventional commitの検証
npx --no -- commitlint --edit $1

# CHANGELOGの生成
npx -- conventional-changelog -p angular -i CHANGELOG.md -s -r 0
```

## 参考情報
- https://qiita.com/ko1nksm/items/09bd50e51cc8663a4f0e
- https://qiita.com/MasaoSasaki/items/f10ab4cd54e228fb436f