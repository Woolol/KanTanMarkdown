# かんたんMarkdown
かんたんMarkdownは完全に単一のHTMLファイルで動作するMarkdownエディタ・プレビューアです。

次のURLにもう少し詳しい説明があります。

http://tatesuke.github.io/KanTanMarkdown/

## リリースノート
### v1.20160130.01

####バグ修正
・初期起動時にシンタックスハイライトが効いていないバグを修正

### v1.20160129.02

#### 仕様変更
* ファイルサイズの肥大化を防ぐため、保存時previewerの中身を削除するようにした

### v1.20160129.01

#### バグ修正
* 保存するとエディタやプレビューのスクロールバーが動いてしまう問題を解決
* ファイル末尾に不要タグが溜まっていく不具合を修正

#### 機能追加
* 自動更新のon/off機能を追加した

### v1.20160128_03

#### バグ修正

* 印刷時レイアウトが激しく崩れる問題を修正

### v1.20160128_02

#### 改善
* 閲覧モード時に横幅が大きすぎたので改善 

### v1.20160128_01

#### 改善
* h1がなくなった時のタイトルを[無題]にした

#### 機能追加
* info, warn, alertクラスを使うことで、青、黃色、赤枠を使えるようにした
* sequenceクラス,flowクラスを使うことでjs-sequence-diagramsとflowchart.jsを利用できるようにした


### v1.20160127_03

#### バグ修正
* スクロールバーが最下部で固定されないバグを修正

### v1.20160127_02

#### 改善
* プレビュー領域が最下部にある時は、内容更新後も最下部に固定するようにした
 + テキストエリアとプレビューのスクロールバー同期は難しそうだだったのでその代替案として
* 添付ファイルを削除する前にプロンプトを表示するようにした
* ソースコードハイライトの自動言語判定をやめ、手動指定にした

### v1.20160127_01

#### バグ修正
* 画像名を変更すると画像を表示できなくなっていたのを修正
* 画像名変更時にid属性から値を引っ張ってきているのを修正
* hrが表示されない不具合を解決

#### 機能追加、改善
* シンタックスハイライト導入
* テーブルの罫線が2重になっていたのを修正

#### 内部改善
* 画像をscriptタグに埋め込むとき、画像名はname属性に埋め込むようにした
* js内でファイルドラッグ時のスタイル適応をハードコーディングしていたのをやめた

### v1.20160126_01
* 保存のたびに</body>の前の改行が増えていくバグを修正
* MITライセンスとしました
* タブキーでタブが入力されるようにした

### v1.20160125_01
* ファイルを開いた時点では閲覧モードになるようにした
* 初期モードは閲覧モードにした
* 複数ファイル添付時の名前がおかしい問題を解決
* IEでも保存できるようにした

### v1.20160124_01
* リリース
