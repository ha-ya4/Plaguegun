# Plaguegun

RimWorldの[Modチュートリアル](https://ludeon.com/forums/index.php?topic=33219.0)やってみた

### MEMO
---

#### プロジェクト作成

- Sourceの中でC＃クラスライブラリ.NETFrameworkプロジェクトを作成（.NETFramework 3.5）

- vs用.gitignore作成はたぶんこれでいい
```
dotnet new gitignore
```

#### Defs
- キャラクター、動物、床、損傷、建物、病気など全てDefsを使って作られてるらしい
- Defsの中は好きな名前でディレクトリを作成することができる