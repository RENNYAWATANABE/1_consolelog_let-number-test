# 1_consolelog_let-number-test

## 🧪 JavaScript 基礎動作確認スクリプト

このスクリプトは、JavaScriptの基本構文（`console.log`、変数宣言、再代入、条件分岐など）の動作を確認するためのサンプルコードです。

---

## 📄 内容の説明

### 1. コンソール出力テスト

```javascript
console.log("consoleTEST確認");
```

- `console.log()` を使って、コンソールにテキストを表示する基本例です。

---

### 2. 変数の宣言と出力

```javascript
let number = 8888;
console.log(number);
```

- `let` を使って `number` を宣言し、初期値を `8888` に設定。
- その値を `console.log()` で出力します。

---

### 3. 変数の再代入

```javascript
number = 10000;
console.log(number);
```

- 変数 `number` の値を `10000` に変更し、再度出力します。

---

### 4. 条件分岐（※コメントアウトされた状態）

```javascript
// if (number > 10000) {
//   console.log("10000より大きい");
// } else {
//   console.log("10000以下");
// }
```

- `number` の値が `10000` を超えているかどうかで出力を変える `if` 文のサンプルです。
- 現在はコメントアウトされているため、実行されません。
- `&gt;` はHTMLエンティティであり、JavaScriptでは `>` に修正する必要があります。

✅ 正しい構文例：

```javascript
if (number > 10000) {
  console.log("10000より大きい");
} else {
  console.log("10000以下");
}
```

---

### 5. テキストの出力

```javascript
console.log("text表記");
```

- 通常の文字列出力の例です。

---

### 6. 定数の宣言と出力

```javascript
const name = 19990913;
console.log(name);
```

- `const` を使って `name` という定数を定義し、数値を代入。
- その値をコンソールに出力します。

---

## ⚠️ 注意点

- 条件分岐の `if` 文は、正しい構文に修正する必要があります（上記参照）。

---

## 🚀 実行方法

1. Node.js がインストールされていることを確認
2. このコードを `index.js` などのファイルに保存
3. ターミナルで以下のコマンドを実行

```bash
node index.js
```

---

## 🎯 目的

- JavaScriptの基本文法の確認
- `console.log` による出力
- `let` / `const` の使い方
- 変数の代入と再代入
- 条件分岐の基礎理解

---
