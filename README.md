# ZenzaWatch

Ginzaから独立して単体で動くHTML5版ニコニコ動画プレイヤーです。
Greasemonkeyスクリプトとして動作します。


## ライセンス

`master` から分岐させたコードにライセンスするなら CC0 あるいは WTFPL あたり


## インストール

[dist](/dist) から `*.user.js` を開き raw ボタンを押すことでインストールできます

## 配布

この fork では `dist/ZenzaWatch-dev.user.js` を開発版、
`dist/ZenzaWatch.user.js` を安定版として配布します。
`@downloadURL` はこの fork の `playlist-deploy` ブランチを指します。

配布先を変える場合はビルド時に上書きできます。

```bash
node build.js --download-base=https://github.com/<owner>/<repo>/raw/<branch>
```

## フィードバック

雑にDiscussionsでコメントしたり、バグの原因がわかってたらIssue開いたり
