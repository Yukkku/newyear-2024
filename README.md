# newyear-2024
プログラマに捧げる年賀状 (2024年版)

[2023年版](https://github.com/Yukkku/2023NewYear)

## 楽しみ方
```sh
node a.js      #=> b.js
node b.js      #=> c.js
node c.js      #=> d.js
node d.js      #=> e.js
node e.js      #=> a.js
```
Nodeで実行すると5つのコードを巡回するQuineになります
```sh
bun run a.js   #=> e.js
bun run b.js   #=> a.js
bun run c.js   #=> b.js
bun run d.js   #=> c.js
bun run e.js   #=> d.js
```
Bunで実行すると逆順になります
```sh
deno run a.js  #=> a.js
deno run b.js  #=> b.js
deno run c.js  #=> c.js
deno run d.js  #=> d.js
deno run e.js  #=> e.js
```
Denoで実行すると自身を出力します
```sh
du -b a.js b.js c.js d.js e.js
# 2024    a.js
# 2024    b.js
# 2024    c.js
# 2024    d.js
# 2024    e.js
```
5つのコードは全て2024Byteです
