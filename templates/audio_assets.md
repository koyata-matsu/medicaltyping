# 音素材のファイル構成と命名

以下の4種＋正解音＋ゲーム終了音（オプション）を想定したシンプル構成です。

```
assets/
  audio/
    bgm/
      game_main.mp3
      game_main.ogg
    sfx/
      click.mp3
      click.ogg
      correct.mp3
      correct.ogg
      typing.mp3
      typing.ogg
      miss.mp3
      miss.ogg
      game_end.mp3
      game_end.ogg
```

## 用途
- `click`：ゲーム全体のボタンのクリック音
- `game_main`：ゲーム中BGM（ループ前提）
- `typing`：タイピング音
- `correct`：正解時の音
- `miss`：タイピングミス音
- `game_end`：ゲーム終了時の音（結果表示など）

## 補足
- まずは `mp3` だけでも動作可能です（互換性を考えるなら `ogg` も推奨）。
- クリック/タイピング/正解/ミス/終了音は短め（0.1〜0.5秒程度）が扱いやすいです。
