# Space Shooter

HTML5 CanvasとJavaScriptで作ったレトロ風シューティングゲーム

## プレイする

https://space-shooter-b5m9c43ox-hotakas-projects.vercel.app

## 機能

- エンジン炎アニメーション付きスペースシャトル
- 3種類の敵キャラクター
  - **UFO** (100点) - 左右にふらふら動く
  - **隕石** (200点) - 回転しながら落下
  - **エイリアン** (300点) - プレイヤーを追尾
- レベルシステム - 敵が10体通過するごとに難易度上昇
- Web Audio APIによるレトロ風効果音
- ハイスコア保存（localStorage）
- Xでスコアをシェア
- スマホ対応タッチ操作

## 操作方法

### PC
| キー | アクション |
|-----|--------|
| ← → | 左右移動 |
| ↑ / スペース | 発射 |

### スマホ
- **◀ ▶** ボタンで移動
- **FIRE** ボタンで発射
- 画面タップでゲーム開始

## 技術スタック

- HTML5 Canvas
- JavaScript
- Web Audio API（外部音声ファイル不要）
- CSS3

## ローカル開発

```bash
# リポジトリをクローン
git clone https://github.com/hotaka0908/space-shooter.git

# ブラウザで開く
open index.html

# またはローカルサーバーを起動
python3 -m http.server 8080
```

## ライセンス

MIT
