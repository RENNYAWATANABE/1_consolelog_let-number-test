# 1_consolelog_let-number-test

# JavaScript 基礎動作確認スクリプト

このスクリプトは、JavaScriptの基本的な構文（`console.log`、変数宣言、再代入、条件分岐など）の動作確認用コードです。

---

## 📄 内容の説明

### 1. コンソール出力テスト
```javascript
console.log("consoleTEST確認");

•	console.log() を使って、コンソールにテキストを表示する基本例です。

⸻

### 2. 変数の宣言と出力
let number = 8888;
console.log(number);

	•	let を使って number を宣言し、初期値を 8888 に設定。
	•	その値を console.log() で出力。

⸻

3. 変数の再代入
number = 10000;
console.log(number);
•	変数 number の値を 10000 に変更し、再度出力。

⸻

4. 条件分岐（※コメントアウトされた状態）
// if (number > 10000) {
//   console.log("10000より大きい");
// } else {
//   console.log("10000以下");
// }

•	number の値が 10000 を超えているかどうかで出力を変える if 文のサンプル。
	•	現在はコメントアウトされているため動作しません。
	•	if の構文に誤りがあるため、修正する必要があります（詳細は下記参照）。

⸻

5. テキストの出力

console.log("text表記");

	•	通常の文字列出力例です。

⸻

6. 定数の宣言と出力

const name = 19990913;
console.log(name);

•	const で name という定数を定義し、数値を代入。
	•	その値をコンソールに出力。

🛠 注意点
	•	if 文の構文が誤っているため、正しく動作させたい場合は以下のように修正してください。

✅ 正しい条件分岐の例:

if (number > 10000) {
  console.log("10000より大きい");
} else {
  console.log("10000以下");
}

🚀 実行方法
	1.	node がインストールされていることを確認
	2.	このコードを index.js などのファイルに保存
	3.	ターミナルで以下のコマンドを実行

node index.js

📚 目的
	•	JavaScriptの基本文法の確認
	•	console.log による出力
	•	let / const の使い方
	•	変数の代入と再代入
	•	条件分岐の基礎





























