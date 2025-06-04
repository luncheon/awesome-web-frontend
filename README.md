# Awesome Web Frontend

自分用 Web フロントエンドライブラリメモ。

## DOM 差分レンダリング

| 名前            | リポジトリ                                | 備考 |
| --------------- | ----------------------------------------- | ----- |
| Solid           | https://github.com/ryansolid/solid        | |
| Preact          | https://github.com/preactjs/preact        | |
| lit-html        | ~~https://github.com/polymer/lit-html~~<br>https://github.com/lit/lit/tree/main/packages/lit-html | |
| ~~jsx-lite~~<br>Mitosis | ~~https://github.com/BuilderIO/jsx-lite~~<br>https://github.com/BuilderIO/mitosis | |
| ~~Sinuous~~     | https://github.com/luwes/sinuous          | |
| ~~Vidact~~      | https://github.com/mohebifar/vidact       | |
| ~~Brahmos~~     | https://github.com/brahmosjs/brahmos      | |
| ~~incremental-dom~~ | https://github.com/google/incremental-dom | [babel-plugin-transform-incremental-dom](https://github.com/jridgewell/babel-plugin-transform-incremental-dom) |
| Voby            | https://github.com/vobyjs/voby            | |
| hybrids         | https://github.com/hybridsjs/hybrids      | |

## 状態管理

| 名前 | リポジトリ | 備考 |
| -------- | ----------------------------------- | ---- |
| MobX     | https://github.com/mobxjs/mobx      |      |
| Immer    | https://github.com/immerjs/immer    |      |
| Mutative | https://github.com/unadlib/mutative | faster Immer |

## メモ化

| 名前        | リポジトリ                                  | 備考                                                     |
| ----------- | ------------------------------------------- | -------------------------------------------------------- |
| memoize-one | https://github.com/alexreardon/memoize-one/ |                                                          |
| Reselect    | https://github.com/reduxjs/reselect         | 全状態を単一オブジェクトに詰め込んでいる場合に限り有効。 |

## CSS in JS

| 名前         | リポジトリ                                 | 備考 |
| ------------ | ------------------------------------------ | ---- |
| Linaria      | https://github.com/callstack/linaria       |      |
| style9       | https://github.com/johanholmerin/style9    |      |
| ~~cssed~~    | https://github.com/okotoki/cssed           |      |
| ~~Compiled~~ | https://github.com/atlassian-labs/compiled |      |
| ~~LightwindCSS~~ | https://github.com/uhyo/lightwindcss       |      |

## Utility CSS

| 名前            | リポジトリ                                      | 備考 |
| ------------------------ | -------------------------------------------------------- | ---- |
| tailwindcss              | https://github.com/tailwindlabs/tailwindcss              |      |
| tailwindcss-intellisense | https://github.com/tailwindlabs/tailwindcss-intellisense | https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss |
| tailwindcss-classnames   | https://github.com/muhammadsammy/tailwindcss-classnames  |      |
| twind                    | https://github.com/tw-in-js/twind                        |      |
| twin.macro               | https://github.com/ben-rogerson/twin.macro               |      |
| ~~xwind~~                | https://github.com/Arthie/xwind                          |      |
| ~~Typed Tailwind~~       | https://github.com/thien-do/typed.tw                     |      |
| Windi CSS                | https://github.com/windicss/windicss                     |      |
| UnoCSS                   | https://github.com/unocss/unocss                         |      |
| Master CSS               | https://github.com/master-co/awesome-master-css          |      |


## フォーム

### バリデーション

| 名前 | リポジトリ                     | 備考 |
| ---- | ------------------------------ | ---- |
| Vest | https://github.com/ealush/vest | |
| Yup  | https://github.com/jquense/yup | |

## UI 要素

### ツールチップ

| 名前             | リポジトリ                                 | 備考                                                                                                                                              |
| ---------------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Balloon.css      | https://github.com/kazzkiq/balloon.css     | CSS カスタムプロパティが利用されている（そのままでは IE 11 で動かなそう）。                                                                       |
| Hint.css         | https://github.com/chinchang/hint.css      | `[class*="hint--"]` のようなセレクターが使われている。古いベンダープレフィックス付きの `-moz-transform` や `-moz-transition` が使われていて冗長。 |
| Tlite            | https://github.com/chrisdavies/tlite       | `title` 属性を見てくれるので既存コードへの適用がラク。                                                                                            |
| html5tooltips.js | https://github.com/ytiurin/html5tooltipsjs | 表示アニメーションのプリセットがいくつかあっておもしろい（ただし実際のプロダクトではツールチップが目を引いちゃダメ）。                            |
| ~~Tootik~~       | https://github.com/eliortabeka/tootik      | ツールチップ本体表示後、遅れて吹き出しの尻尾が出てくる。この挙動が気になるので使えない。                                                          |
| ~~Microtip~~     | https://github.com/ghosh/microtip          | 対象要素に `role="tooltip"` を付与しなければならない奇妙仕様。                                                                                    |
| ~~Tippy.js~~     | https://github.com/atomiks/tippyjs         | Popper ベース。重い。                                                                                                                             |

### トースト

| 名前      | リポジトリ                             | 備考 |
| --------- | -------------------------------------- | ---- |
| Toastify  | https://github.com/apvarun/toastify-js |      |
| toastedjs | https://github.com/shakee93/toastedjs  |      |

### 進捗表示

| 名前          | リポジトリ                                     | 備考 |
| ------------- | ---------------------------------------------- | ---- |
| topbar        | https://github.com/buunguyen/topbar            |    |
| Rsup Progress | https://github.com/skt-t1-byungi/rsup-progress |    |
| ~~Pace.js~~   | https://github.com/HubSpot/pace                | XHR 時代は何も考えずに使えて非常に便利だった。既知のメモリリークがある。 ~~今後メンテナンスしないと明言されている。~~ 移管されてメンテナンス再開されてるっぽい。 |

### モーダル

| 名前              | リポジトリ                                      | 備考 |
| ----------------- | ----------------------------------------------- | ---- |
| html-native-modal | https://github.com/luncheon/html-native-modal   | `<dialog>` は `z-index` に関係なく他の absolute / fixed / sticky 要素より手前に表示されるので、ツールチップやトーストなどポップアップと相性が悪い場合がある。 |
| Modal Vanilla     | https://github.com/KaneCohen/modal-vanilla      |      |
| Micromodal.js     | https://github.com/Ghosh/micromodal             |      |
| HystModal         | https://github.com/AddMoreScripts/hystModal     |      |
| ~~tingle.js~~     | https://github.com/robinparisi/tingle           | 背景が全く見えなくなる。<br>閉じるときアニメーションがない。   |
| ~~A11y Dialog~~   | https://github.com/edenspiekermann/a11y-dialog/ | マークアップが非常に煩雑。<br>閉じるときアニメーションがない。 |

### ウィンドウ

| 名前 | リポジトリ | 備考 |
| ---- | ---- | ---- |
| Golden Layout | https://github.com/golden-layout/golden-layout | |

### タブ

| 名前  | リポジトリ                           | 備考 |
| ----- | ------------------------------------ | ---- |
| Tabby | https://github.com/cferdinandi/tabby |      |

### ペイン分割

| 名前 | リポジトリ                     | 備考 |
| ---- | ------------------------------ | ---- |
| flex-splitter-directive | https://github.com/luncheon/flex-splitter-directive |  |
| Split | https://github.com/nathancahill/split/ |  |

### カルーセル

| 名前           | リポジトリ                                       | 備考 |
| -------------- | ------------------------------------------------ | ---- |
| Flicking       | https://github.com/naver/egjs-flicking           |      |
| Embla Carousel | https://github.com/davidcetinkaya/embla-carousel |      |
| Splide         | https://github.com/Splidejs/splide               |      |

### 複数選択ボックス

| 名前             | リポジトリ                                            | 備考 |
| ---------------- | ----------------------------------------------------- | ---- |
| elab             | https://github.com/luncheon/elab                      | スクリプト記述不要 |
| Virtual Select   | https://github.com/sa-si-dev/virtual-select           |      |
| vanillaSelectBox | https://github.com/PhilippeMarcMeyer/vanillaSelectBox |      |
| Choices.js       | https://github.com/jshjohnson/Choices                 |      |
| \<multiselect-combo-box\> | https://github.com/gatanaso/multiselect-combo-box | Polymer |

### Date Picker

| 名前    | リポジトリ                         | 備考 |
| ------- | ---------------------------------- | ---- |
| `<input type="date">` |  | もうこれで十分 |
| Pikaday | https://github.com/Pikaday/Pikaday |      |

### Time Picker

| 名前     | リポジトリ                           | 備考 |
| -------  | ------------------------------------ | ---- |
| Clocklet | https://github.com/luncheon/clocklet |      |

### 手書き風

| 名前          | リポジトリ                                       | 備考 |
| -------------- | --------------------------------------------- | ---- |
| Rough.js       | https://github.com/rough-stuff/rough          | SVG または Canvas に描画するグラフィックスライブラリ |
| Rough Notation | https://github.com/rough-stuff/rough-notation | 下線や囲み線などによる装飾ライブラリ |
| Chart.xkcd     | https://github.com/timqian/chart.xkcd         | グラフライブラリ |
| roughViz.js    | https://github.com/jwilber/roughViz           | グラフライブラリ／要 D3.js |

## SVG

| 名前 | リポジトリ | 備考 |
| ------------------- | ------------------------------------------------------ | ----- |
| svgo                | https://github.com/svg/svgo                            | SVG Optimizer |
| svg-path-properties | https://github.com/rveciana/svg-path-properties        | `<path>` の `getPointAtLength()` と `getTotalLength()` |
| svgpath             | https://github.com/fontello/svgpath                    | `<path>` のアフィン変換 |
| svg-path-bbox       | https://github.com/mondeja/svg-path-bbox               | `<path>` のバウンディングボックス計算（上の svgpath 依存） |
| SVGCatmullRomSpline | https://github.com/SatoshiKawabata/SVGCatmullRomSpline | 点の配列を曲線で結ぶ（Catmull-Rom Spline 補完） |
| simplify-svg-path   | https://github.com/luncheon/simplify-svg-path          | 点の配列を曲線で近似（Paper.js から当該機能だけ切り出したモジュール） |
| svg-path-morph      | https://github.com/Minibrams/svg-path-morph            | 複数パス間のモーフィング（中間パス） |

## Canvas

| 名前      | リポジトリ                            | 備考 |
| --------- | ------------------------------------- | ---- |
| Fabric.js | https://github.com/fabricjs/fabric.js | |
| Konva.js  | https://github.com/konvajs/konva | |
| Two.js    | https://github.com/jonobr1/two.js | |
| iDraw.js  | https://github.com/idrawjs/idraw | |

## データテーブル

| 名前          | リポジトリ                                       | 備考 |
| ------------- | ------------------------------------------------ | ---- |
| agGrid        | https://github.com/ag-grid/ag-grid               | Enterprise 版は有料（商用利用有料って紹介してる記事もあるけど大丈夫そう） |
| Grid.js       | https://github.com/grid-js/gridjs                | |
| Cheetah Grid  | https://github.com/future-architect/cheetah-grid | Canvas に表を描画する。 |

### スプレッドシート

| 名前            | リポジトリ                                    | 備考 |
| ---------------- | ------------------------------------------- | ---- |
| Importabular     | https://github.com/renanlecaro/importabular | 編集可能な文字列テーブル（表計算というよりフォームの代替） |
| Luckysheet       | https://github.com/mengshukeji/Luckysheet   | 非常に高機能な表計算ライブラリ（Canvas, jQuery UI, font-awesome, echarts）。 |
| FortuneSheet     | https://github.com/ruilisi/fortune-sheet    | TypeScript で書き直された Luckysheet。まだ機能不足、今後に期待 |
| x-spreadsheet    | https://github.com/myliang/x-spreadsheet    | Canvas ベースの表計算ライブラリ。 Luckysheet の方が高機能なので出番はなさそうか |
| ~~jExcel~~<br>Jspreadsheet | ~~https://github.com/paulhodel/jexcel~~<br>https://github.com/jspreadsheet/ce | Table ベースの表計算ライブラリ（Canvas と違って CSS が効くので扱いやすい場合がある）。有償版あり。 Luckysheet の方が高機能なので出番はなさそうか |
| ~~Handsontable~~ | https://github.com/handsontable/handsontable/tree/develop/handsontable | [商用版は非常に高価](https://handsontable.com/pricing)。数式評価が [Hyperformula](https://github.com/handsontable/hyperformula) として切り出されているがこちらの商用利用はサポート問い合わせ。 |
| ~~Rows n' Columns~~ | https://github.com/rowsncolumns/grid     | [商用は高価](https://rowsncolumns.app/pricing) |
| RevoGrid         | https://github.com/revolist/revogrid        | MIT ライセンスのスプレッドシートコンポーネント。 |
| SheetJS          | https://github.com/SheetJS/sheetjs          | 多様なスプレッドシートファイル形式の読み書き |
| ExcelJS          | https://github.com/exceljs/exceljs          | xlsx ファイルの読み書きと操作 |
| xlsx-populate    | https://github.com/dtjohnson/xlsx-populate  | xlsx ファイルの読み書きと操作 |

### 仮想スクロール

| 名前          | リポジトリ                                       | 備考 |
| ------------- | ------------------------------------------------ | ---- |
| Clusterize.js | https://github.com/NeXTs/Clusterize.js           | |

## リスト並べ替え

| 名前      | リポジトリ                            | 備考 |
| --------- | ------------------------------------- | ---- |
| SortableJS | https://github.com/SortableJS/Sortable | |
| Dragula | https://github.com/bevacqua/dragula | |

## Sticky

| 名前      | リポジトリ                            | 備考 |
| --------- | ------------------------------------- | ---- |
| HC-Sticky | https://github.com/somewebmedia/hc-sticky | |

## グラフ

| 名前           | リポジトリ                                   | 備考 |
| -------------- | -------------------------------------------- | ---- |
| Chart.js       | https://github.com/chartjs/Chart.js          | |
| APEXCHARTS.JS  | https://github.com/apexcharts/apexcharts.js | |
| C3.js          | https://github.com/c3js/c3                   | 要 D3.js         |
| billboard.js   | https://github.com/naver/billboard.js        | C3.js のフォーク |
| morris.js      | https://github.com/morrisjs/morris.js        | 要 jQuery        |
| Flot           | https://github.com/flot/flot                 | 要 jQuery        |
| Plotly         | https://github.com/plotly/plotly.js          | |
| Apache ECharts | https://github.com/apache/echarts            | |

## ミニグラフ

| 名前       | リポジトリ                                 | 備考      |
| ---------- | ------------------------------------------ | --------- |
| Peity      | https://github.com/benpickles/peity        | 要 jQuery |
| Sparklines | https://github.com/gwatts/jquery.sparkline | 要 jQuery |

## CSS フレームワーク

### Material Design

| 名前            | リポジトリ                             | 備考   |
| --------------- | -------------------------------------- | ------ |
| MUI             | https://github.com/muicss/mui          |        |
| ~~Materialize~~ | https://github.com/Dogfalo/materialize | 重い。 |

### テーマ

| 名前        | ホームページ                             | 備考   |
| ----------- | -------------------------------------- | ------ |
| 98.css     | https://jdan.github.io/98.css/          | A CSS library for building interfaces that look like Windows 98 |
| XP.css     | https://botoxparty.github.io/XP.css/    | A CSS library for building interfaces that look like old UIs |
| System.css | https://sakofchit.github.io/system.css/ | A CSS library for building interfaces that resemble Apple's System OS which ran from 1984-1991 |

## アイコンセット

| 名前                  | ホームページ                              | 備考 |
| --------------------- | -------------------------------------- | ---- |
| Blendicons            | https://blendicons.com/free-icons      |      |
| Iconduck              | https://iconduck.com/                  |      |
| Fluent Icons          | https://fluenticons.co/                |      |
| Material Design Icons | https://materialdesignicons.com/       |      |
| Phosphor              | https://phosphoricons.com/             |      |
| MingCute Icon         | https://www.mingcute.com/              |      |
| lineicons             | https://lineicons.com/                 |      |
| Glyphs                | https://glyphs.fyi/dir                 |      |
| Iconicons             | https://ionicons.com/                  |      |
| Feather               | https://feathericons.com/              |      |
| Lucide                | https://lucide.dev/icons/              | Feather Icons のフォーク |
| ~~Emblemicons~~           | ~~https://emblemicons.in/#icons~~          | ドメイン手放したっぽい |
| Eva Icons             | https://akveo.github.io/eva-icons      |      |
| Remix Icon            | https://remixicon.com/                 |      |
| Ikonate               | https://ikonate.com/                   |      |
| Unicons               | https://iconscout.com/unicons          |      |
| Teenyicons            | https://teenyicons.com/                |      |
| Tabler Icons          | https://tablericons.com/               |      |
| Heroicons             | https://heroicons.com/                 |      |
| Font Awesome          | https://fontawesome.com/               |      |
| Line Awesome          | https://icons8.com/line-awesome        |      |
| IconPark              | http://iconpark.bytedance.com/official |      |
| Color Icons           | https://icons8.com/icons/color         |      |
| css.gg                | https://css.gg/                        |      |
| IcoMoon               | https://icomoon.io/app/#/select        |      |
| Akar Icons            | https://akaricons.com/                 |      |
| Iconoir               | https://iconoir.com/                   |      |
| Boxicons              | https://boxicons.com/                  |      |
| Doodle Icons          | https://khushmeen.com/icons.html       |      |
| Humbleicons           | https://humbleicons.com/               |      |
| iconir                | https://iconoir.com/                   |      |
| Sargam Icons          | https://sargamicons.com/               |      |
| Pixel Icon Library    | https://pixeliconlibrary.com/          |      |
| pqoqubbw/icons        | https://icons.pqoqubbw.dev/            | アニメーション付きアイコン |

### ローディングアイコン

| 名前 | ホームページ | 備考 |
| ---- | ---- | ---- |
| Open Source SVG Loading Icons | https://magecdn.com/tools/svg-loaders |      |

### ブランドアイコンセット

| 名前         | ホームページ             | 備考 |
| ------------ | ------------------------ | ---- |
| Simple Icons | https://simpleicons.org/ |      |

### アイコンセット検索

| 名前                  | ホームページ                              | 備考 |
| --------------------- | -------------------------------------- | ---- |
| Iconer                | https://iconer.app/                    |      |

## イラスト

| 名前 | ホームページ | 利用規約 | 備考 |
| ---- | ---- | ---- | ---- |
| いらすとや | https://www.irasutoya.com/ | https://www.irasutoya.com/p/terms.html | |
| イラストセンター | https://illustcenter.com/ | https://illustcenter.com/terms/ | |
| shigureni | https://www.shigureni.com/ | https://www.shigureni.com/terms-of-use | |
| 商用利用無料、国内のフリーイラスト素材の総まとめ | https://coliss.com/articles/freebies/freebies-illustrations.html | | |

## 写真素材

| 名前 | ホームページ | 利用規約 | 備考 |
| ---- | ---- | ---- | ---- |
| ぱくたそ | https://www.pakutaso.com/ | https://www.pakutaso.com/userpolicy.html | |
| フリービーAC | https://www.freebie-ac.jp/ | https://www.freebie-ac.jp/terms.php | 要ユーザー登録 |
| スキマナース | https://nurse-web.jp/photo/ | | |

## プレゼンテーション

| 名前       | ホームページ                                  | 備考 |
| ---------- | --------------------------------------------- | ---- |
| reveal.js  | https://revealjs.com/                         |      |
| Bespoke.js | http://markdalgleish.com/projects/bespoke.js/ |      |

## 文書

| 名前 | リポジトリ | 備考 |
| ---- | ---- | ---- |
| docx          | https://github.com/dolanmiu/docx               | .docx ファイル作成 |
| docxjs        | https://github.com/VolodymyrBaydalka/docxjs    | .docx 描画 |
| PDF.js        | https://github.com/mozilla/pdf.js              | PDF を Canvas に描画 |
| PDF-LIB       | https://github.com/Hopding/pdf-lib             | PDF ファイル作成 |
| PDFKit        | https://github.com/foliojs/pdfkit              | PDF ファイル作成 |
| jsPDF         | https://github.com/parallax/jsPDF              | PDF ファイル作成 |
| open-pdf-sign | https://github.com/open-pdf-sign/open-pdf-sign | PDF 署名 |

## 3D Model

| 名前 | リポジトリ | 備考 |
| ---- | ---- | ---- |
| &lt;model-viewer&gt; | https://github.com/google/model-viewer    | glTF & GLB viewer |
| CascadeStudio        | https://github.com/zalo/CascadeStudio     | |
| Online 3D Viewer     | https://github.com/kovacsv/Online3DViewer | |

## Type / Schema Validation

| 名前 | リポジトリ | 備考 |
| ------------------------- | ------------------------------------------------------ | ---- |
| Zod                       | https://github.com/colinhacks/zod                      | TypeScript DSL -> TypeScript Types, Runtime Validator, JSON Schema |
| Runtypes                  | https://github.com/pelotom/runtypes                    | TypeScript DSL -> TypeScript Types, Runtime Validator (, JSON Schema) |
| io-ts                     | https://github.com/gcanti/io-ts                        | TypeScript DSL -> TypeScript Types, Runtime Validator |
| Superstruct               | https://github.com/ianstormtaylor/superstruct          | TypeScript DSL -> TypeScript Types, Runtime Validator |
| TypeBox                   | https://github.com/sinclairzx81/typebox                | TypeScript DSL -> TypeScript Types, JSON Schema |
| TypeScript-JSON           | https://github.com/samchon/typescript-json             | TypeScript Types -> Runtime Type Validator, JSON Schema (TypeScript Plugin) |
| typescript-is             | https://github.com/woutervh-/typescript-is             | TypeScript Types -> Runtime Type Validator (TypeScript Plugin) |
| ts-runtime                | https://github.com/fabiandev/ts-runtime                | TypeScript Types -> Runtime Type Validator (API/CLI でコード変換) |
| type-predicates-generator | https://github.com/d-kimuson/type-predicates-generator | TypeScript Types -> Runtime Type Validator (CLI でコード生成) |
| ts-auto-guard             | https://github.com/rhys-vdw/ts-auto-guard              | TypeScript Types -> Runtime Type Validator (CLI でコード生成) |
| typescript-json-schema    | https://github.com/YousefED/typescript-json-schema     | TypeScript Types -> JSON Schema (API/CLI) |
| Ajv                       | https://github.com/ajv-validator/ajv                   | JSON Schema Validator |

## パーサージェネレーター

| 名前 | リポジトリ | 備考 |
| ------- | ------------------------------- | ---- |
| PEG.js  | https://github.com/pegjs/pegjs  |  |
| Ohm     | https://github.com/harc/ohm     |  |
| nearley | https://github.com/kach/nearley |  |

## TypeScript

| 名前 | リポジトリ | 備考 |
| ---- | ---- | ---- |
| ts-essentials | https://github.com/ts-essentials/ts-essentials | |
| type-fest     | https://github.com/sindresorhus/type-fest      | |
| ts-toolbelt   | https://github.com/millsp/ts-toolbelt          | |

## その他

| 名前   | リポジトリ                      | 備考 |
| -------------- | --------------------------------------------- | ---- |
| Magic bytes    | https://github.com/LarsKoelpin/magic-bytes    | ファイルの内容からファイルの種類を判定 |
| GPU.js         | https://github.com/gpujs/gpu.js               | |
| Parallel.js    | https://github.com/parallel-js/parallel.js    | |
| lz-string      | https://github.com/pieroxy/lz-string          | 高速なテキスト圧縮 `compressToUTF16()`<br> https://pieroxy.net/blog/pages/lz-string/demo.html |
| LZ-UTF8        | https://github.com/rotemdan/lzutf8.js         | 高速なテキスト圧縮 |
| opentype.js    | https://github.com/opentypejs/opentype.js     | ttf, otf, woff ファイル読み書き |
| Moji.js        | https://github.com/niwaringo/moji             | 半角全角変換ライブラリ |
| YubinBango     | https://github.com/yubinbango/yubinbango-data | 郵便番号 → 住所データ |
| ScrollBooster  | https://github.com/ilyashubin/scrollbooster   | ドラッグで慣性スクロール |
| Chrome Network Log | chrome://net-export/ | |
