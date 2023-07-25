# roulette-base
ルーレットの色と番号をjson形式でまとめたものです。カジノ風ルーレットを作るときにどうぞ。<br>
A collection of roulette colors and numbers in json format. Use it when making a casino-style roulette.

使い方の例 (Usage example):
```js
const result = require("./roulette.json");

console.log(result.roulette[0].color); // null
console.log(result.roulette[0].number); // 0
console.log(result.roulette[1].color); // red
console.log(result.roulette[1].number); // 1
console.log(result.roulette[2].color); // black
console.log(result.roulette[2].number); // 2
console.log(result.roulette[Math.floor(Math.random() * 37)].color); // null or red or black
console.log(result.roulette[Math.floor(Math.random() * 37)].number); // 0-36
```
