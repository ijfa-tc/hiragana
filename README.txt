ひらがな なぞり練習（ウェブ版）

■ 中身
index.html … アプリ本体
manifest.json … ホーム画面に追加するための情報
sw.js … オフラインで動かすためのファイル
icons/ … アプリのアイコン

■ 更新するとき
index.html を差し替えたら、sw.js の1行目
const CACHE="hiragana-v1"; の数字を v2, v3… と1つ上げてください。
これで生徒のスマホにも新しい版が届きます。

■ クレジット
書き順データ: KanjiVG (http://kanjivg.tagaini.net) CC BY-SA 3.0, © Ulrich Apel
