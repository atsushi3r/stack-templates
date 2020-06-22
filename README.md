## 使い方
`stack new` をする際にテンプレートファイルのパスを指定する。
```sh
stack new ${project_name} github:atsushi3r/myplain
```

または、$HOME/.stack/config.yaml に以下を追加する。
```
default-template: github:atsushi3r/myplain
```
