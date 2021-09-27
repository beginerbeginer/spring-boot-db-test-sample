# spring-boot-db-test-sample
[![.github/workflows/ci.yaml](https://github.com/ningenMe/spring-boot-db-test-sample/actions/workflows/ci.yaml/badge.svg)](https://github.com/ningenMe/spring-boot-db-test-sample/actions/workflows/ci.yaml)

- `gradle test`実行時にテスト用のdbをdockerで立ち上げる
- dbunitを使ってdbのassertionを行う
- spock / junit でテストを行う


## テストの実行方法
```
gradle test
```

## 参考記事

[spring-boot + dbunit + dockerでdbのテストを行う](https://qiita.com/ningenMe/items/045620965bf73555d0a7)
