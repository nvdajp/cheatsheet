# NVDA Cheat Sheet

- NVDA日本語チーム www.nvda.jp
- rev. 241115 © 2024 nvdajp CC BY 4.0.


## NVDA制御キー (以下NVDAキー)
- Insert
- Caps Lock (英語キーボード)
- 無変換 (NVDA日本語版)

 (2回押すと元のキーの機能)

- Ctrl+Alt+N NVDA起動
- NVDA+N NVDAメニュー
- NVDA+Q NVDAの終了
- NVDA+1 入力ヘルプ開始/終了
- NVDA+Enter 既定アクション実行
- NVDA+スペース モード切替(または自動切替)


## フォーカスモードとブラウズモード

- フォーカスモード
  - ブラウザとコンテンツを操作
- ブラウズモード
  - NVDAがブラウザを制御
- フォーカスモードからブラウズモードへ切り替わるときは「ポン」と音がする
- ブラウズモードからフォーカスモードへ切り替わるときは「ガシャ」と音がする
- Escキーでもフォーカスモードからブラウズモードへ切り替えることができる


## Windows 操作 (フォーカス)
- 矢印キー 移動
- Shift+矢印キー 範囲選択
- Tab/Shift+Tab フォーカス移動
- F6/Shift+F6 ペイン移動
- Enter 項目選択や実行など
- スペース ボタンを押すなど
- Shift+F10 コンテキストメニュー
- Alt+下矢印 コンボボックス展開


## その他
- カンマ コンテナ要素の直後に移動
- Shift+カンマ コンテナ要素の先頭に移動
- NVDA+B 現在のウィンドウに含まれるオブジェクトの読み上げ


## テキストを読む
- NVDA+L 現在の行
- NVDA+A すべて読み上げ	
- NVDA+Shift+S 選択中のテキスト


## レビューカーソル

### ラップトップ配列 (+NVDAキー)
- ピリオド 現在の文字
- 左矢印/右矢印 前の文字 / 次の文字
- Shift+ピリオド 現在の行
- 上矢印/下矢印 前の行 / 次の行
- Ctrl+ピリオド 現在の単語
- Ctrl+左矢印/右矢印 前の単語 / 次の単語

### デスクトップ配列 (テンキー)
| 7 4 1 | 8 5 2 | 9 6 3 |
|--|--|--|
| 前の行 | 現在の行 | 次の行 |
| 前の単語 | 現在の単語 | 次の単語 |
| 前の文字 | 現在の文字 | 次の文字 |

## オブジェクトナビゲーション

### ラップトップ配列 (+NVDAキー)
- Shift+O 現在の要素
- Shift+左矢印/右矢印 前の要素 / 次の要素
- Shift+上矢印/下矢印 親の要素 / 子の要素
- PageUp 次のレビューモード
- PageDown 前のレビューモード
- Shift+[/] 前の要素 / 次の要素 (フラットビュー)

### デスクトップ配列 (テンキー)
| 7 4 1 | 8 5 2 | 9 6 3 |
|--|--|--|
| 次のレビューモード | 親の要素 | 前の要素 (フラットビュー) |
| 前の要素 | 現在の要素 | 次の要素 |
| 前のレビューモード | 子の要素 | 次の要素 (フラットビュー) |


## テーブル
- Ctrl+Alt+矢印キー テーブル内の移動
- NVDA+Ctrl+Alt+左矢印 先頭から行を読み上げ
- NVDA+Ctrl+Alt+右矢印 現在位置から行を読み上げ
- NVDA+Ctrl+Alt+上矢印 先頭から列を読み上げ
- NVDA+Ctrl+Alt+下矢印 現在位置から列を読み上げ


## 報告
- NVDA+Tab フォーカス
- NVDA+T タイトル
- NVDA+D 詳細説明


## 1文字ナビゲーション (Shift+で逆方向)
- H 見出し
- 1〜6 見出し1〜6
- L リスト
- I リスト項目
- T テーブル
- K	リンク
- (NVDA+K)    (報告)
- N	リンクのないテキスト
- F	フォームフィールド
- U	未訪問リンク
- V	訪問済みリンク
- E	エディットフィールド
- B	ボタン
- X	チェックボックス
- C	コンボボックス
- R	ラジオボタン
- M	フレーム
- G	画像
- D	ランドマーク
- O	埋め込みオブジェクト


## 声や音の制御・設定
- Ctrl 読み上げ停止 
- Shift 読み上げ一時停止
- NVDA+S 読み上げモード
- NVDA+M マウスカーソル
- NVDA+U プログレス
- NVDA+P 記号

### 設定変更
- 設定 → 音声 → エンジンなし 
- ツール → スピーチビューアー


## NVDA+F7 要素リスト
- リンク
- 見出し
- フォームフィールド
- ボタン
- ランドマーク
- 閲覧・実行・検索 (Webブラウザの場合)


## NVDA+F  書式とドキュメント情報 (設定で自動報告を無効化できる)
- フォント
- ドキュメント情報
- ページと間隔
- テーブル情報
- 要素


## ビジュアルハイライト
フォーカスとナビゲーターオブジェクトが一致

- 青い実線 フォーカス

フォーカスとナビゲーターオブジェクトが分離

- 青い点線 フォーカス
- 赤い実線 ナビゲーターオブジェクト
- 黄色い実線 ブラウズモードのカーソル
