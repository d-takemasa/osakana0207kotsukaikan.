# リーチアクション用の画像ファイル

以下の画像ファイルを `reach_images` ディレクトリに配置してください：

## 1. キャラクターが右から現れるアクション用
- `character_rush.png` - 右から現れるキャラクター画像（80x80px推奨）

## 2. ロゴが中央にフェードインするアクション用
- `logo_fade.png` - 中央に表示されるロゴ画像（400x400px推奨）

## 3. 上からキャラクターが降りてくるアクション用
- `character_drop.png` - 上から降りてくるキャラクター画像（120x120px推奨）

## 現在の実装について
現在のコードでは、既存の景品画像（`prize_images/prize_S.png`）を使用してリーチアクションを実行しています。

より効果的なリーチアクションを実現するために、上記の専用画像ファイルを作成し、以下のようにHTMLを更新することをお勧めします：

```html
<!-- キャラクターが右から現れるアクション用 -->
<div class="character" style="background-image: url('reach_images/character_rush.png');"></div>

<!-- ロゴが中央にフェードインするアクション用 -->
<div class="logo-image" style="background-image: url('reach_images/logo_fade.png');"></div>

<!-- 上からキャラクターが降りてくるアクション用 -->
<div class="dropping-character" style="background-image: url('reach_images/character_drop.png');"></div>
```

## 画像の推奨仕様
- ファイル形式: PNG（透明背景対応）
- サイズ: 上記の推奨サイズに合わせて作成
- 内容: パチスロのリーチアクションに適したキャラクターやロゴ
- 色: 鮮やかで目立つ色合い
