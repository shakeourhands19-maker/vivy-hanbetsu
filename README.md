# スマスロ Vivy 設定判別・小役カウンター

ブラウザで使う単一HTMLのツールです。

## 公開方法（GitHub Pages）

1. リポジトリの **Settings** を開く
2. 左メニューの **Pages** を開く
3. **Build and deployment** の Source を **Deploy from a branch** にする
4. Branch を **main**、フォルダを **/ (root)** にして **Save**

公開URLは通常、次の形式です。

https://shakeourhands19-maker.github.io/vivy-hanbetsu/

## 機能

- 設定判別：AT初当たり確率、コイン表示、エンディング示唆の入力
- 小役カウント：通常時とAT中を分けて記録
- 実戦記録：日付・メモ付きで保存
- JSONバックアップ／復元

入力データは利用中のブラウザのローカルストレージに保存されます。端末間では共有されません。

## 注意

解析値が確認できていない設定差は推測で補完していません。設定推測の表示は参考値であり、設定を確定するものではありません。