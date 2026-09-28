# 写真の置き場

ファイル名の約束： `art/<器>/<状態>-<向き>.jpg`

- 器：`sphere` `jar` `cube` `round` `oval` `rect`
- 状態：`soil`（土） `sprout`（芽吹き） `lush`（茂り） `dry`（乾き）
- 向き：`p`（縦） `l`（横）

例：`art/sphere/lush-p.jpg`

置いたら `npm run art`（`npm run dev` / `npm run build` でも自動で走る）。
`lush` がある器だけ写真で描き、ない器はこれまでの描画で描く。
向きが片方しかなければ、もう片方は同じ写真を中央で切り抜いて使う。
