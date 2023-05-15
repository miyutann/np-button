# No-Opinion Button / 意見ありませんボタン

## Steps to run the server on local PC / ローカル環境で動作させるための手順

1. Install [node.js](https://nodejs.org/ja/).
2. Clone this repository.
3. Navigate to the repository directory and run `npm install`.
5. Prepare MongoDB server.
6. Write the MongoDB URL to the file ".env.sample".
7. Rename the file ".env.sample" to ".env"
8. Run `node server.js` in the terminal.
9. Open http://localhost:3000/ with the broswer.

## Usage / 使い方
- メモ表示機能 なし http://localhost:3000/?memo=false
- 30秒で復活機能 なし http://localhost:3000/?timeout=true
- ホスト用画面（みんな復活ボタン付） http://localhost:3000/host.html