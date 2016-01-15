herokuへのデプロイ時、`package.json`の`devDependencies`はインストールされない。  
以下の設定を追加することでインストールされるようになる。

```bash
$ heroku config:set NPM_CONFIG_PRODUCTION=false
```
