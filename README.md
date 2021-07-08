# Awesome Web Frontend

自分用 Web フロントエンドライブラリメモ。

## DOM 差分レンダリング

| 名前            | リポジトリ                                | 備考 |
| --------------- | ----------------------------------------- | ----- |
| Solid           | https://github.com/ryansolid/solid        | |
| Sinuous         | https://github.com/luwes/sinuous          | |
| ~~Vidact~~      | https://github.com/mohebifar/vidact       | |
| Brahmos         | https://github.com/brahmosjs/brahmos      | |
| jsx-lite        | https://github.com/BuilderIO/jsx-lite     | |
| lit-html        | https://github.com/polymer/lit-html       | |
| Preact          | https://github.com/preactjs/preact        | |
| incremental-dom | https://github.com/google/incremental-dom | [babel-plugin-transform-incremental-dom](https://github.com/jridgewell/babel-plugin-transform-incremental-dom) |

## 状態管理

| 名前  | リポジトリ                       | 備考 |
| ----- | -------------------------------- | ---- |
| MobX  | https://github.com/mobxjs/mobx   |      |
| Immer | https://github.com/immerjs/immer |      |

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
| cssed        | https://github.com/okotoki/cssed           |      |
| Compiled     | https://github.com/atlassian-labs/compiled |      |
| LightwindCSS | https://github.com/uhyo/lightwindcss       |      |

## Tailwind CSS

| 名前            | リポジトリ                                      | 備考 |
| ------------------------ | -------------------------------------------------------- | ---- |
| tailwindcss              | https://github.com/tailwindlabs/tailwindcss              |      |
| tailwindcss-jit          | https://github.com/tailwindlabs/tailwindcss-jit          |      |
| tailwindcss-intellisense | https://github.com/tailwindlabs/tailwindcss-intellisense | https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss |
| tailwindcss-classnames   | https://github.com/muhammadsammy/tailwindcss-classnames  |      |
| Windi CSS                | https://github.com/windicss/windicss                     |      |
| twind                    | https://github.com/tw-in-js/twind                        |      |
| twin.macro               | https://github.com/ben-rogerson/twin.macro               |      |
| xwind                    | https://github.com/Arthie/xwind                          |      |
| Typed Tailwind           | https://github.com/thien-do/typed.tw                     |      |

## フォーム

### バリデーション

| 名前 | リポジトリ                     | 備考 |
| ---- | ------------------------------ | ---- |
| Vest | https://github.com/ealush/vest |      |

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
| ~~tingle.js~~     | https://github.com/robinparisi/tingle           | 背景が全く見えなくなる。<br>閉じるときアニメーションがない。   |
| ~~A11y Dialog~~   | https://github.com/edenspiekermann/a11y-dialog/ | マークアップが非常に煩雑。<br>閉じるときアニメーションがない。 |

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

## Canvas

| 名前      | リポジトリ                            | 備考 |
| --------- | ------------------------------------- | ---- |
| Fabric.js | https://github.com/fabricjs/fabric.js | |
| Konva.js | https://github.com/konvajs/konva | |
| Two.js    | https://github.com/jonobr1/two.js | |

## データテーブル

| 名前          | リポジトリ                                       | 備考 |
| ------------- | ------------------------------------------------ | ---- |
| agGrid        | https://github.com/ag-grid/ag-grid               | Enterprise 版は有料（商用利用有料って紹介してる記事もあるけど大丈夫そう） |
| Grid.js       | https://github.com/grid-js/gridjs                | |
| Cheetah Grid  | https://github.com/future-architect/cheetah-grid | Canvas に表を描画する。 |

### スプレッドシート

| 名前         | リポジトリ                                       | 備考 |
| ------------- | ------------------------------------------- | ---- |
| jExcel        | https://github.com/paulhodel/jexcel         | |
| Importabular  | https://github.com/renanlecaro/importabular | |
| Luckysheet    | https://github.com/mengshukeji/Luckysheet   | |
| x-spreadsheet | https://github.com/myliang/x-spreadsheet    | |

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

| 名前          | リポジトリ                                   | 備考             |
| ------------- | -------------------------------------------- | ---------------- |
| Chart.js      | https://github.com/chartjs/Chart.js          |                  |
| APEXCHARTS.JS | https://github.com/apexcharts/apexcharts.js |                  |
| C3.js         | https://github.com/c3js/c3                   | 要 D3.js         |
| billboard.js  | https://github.com/naver/billboard.js        | C3.js のフォーク |
| morris.js     | https://github.com/morrisjs/morris.js        | 要 jQuery        |
| Flot          | https://github.com/flot/flot                 | 要 jQuery        |
| Plotly        | https://github.com/plotly/plotly.js          |                  |
| roughViz.js   | https://github.com/jwilber/roughViz          |                  |

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

## アイコンセット

| 名前                  | ホームページ                              | 備考 |
| --------------------- | -------------------------------------- | ---- |
| Fluent Icons          | https://fluenticons.co/                |      |
| Material Design Icons | https://materialdesignicons.com/       |      |
| Glyphs                | https://glyphs.fyi/dir                 |      |
| Iconicons             | https://ionicons.com/                  |      |
| Feather               | https://feathericons.com/              |      |
| Emblemicons           | https://emblemicons.in/#icons          |      |
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

### ブランドアイコンセット

| 名前         | ホームページ             | 備考 |
| ------------ | ------------------------ | ---- |
| Simple Icons | https://simpleicons.org/ |      |

## プレゼンテーション

| 名前       | ホームページ                                  | 備考 |
| ---------- | --------------------------------------------- | ---- |
| reveal.js  | https://revealjs.com/                         |      |
| Bespoke.js | http://markdalgleish.com/projects/bespoke.js/ |      |

## 型チェック

| 名前       | リポジトリ                                    | 備考 |
| ---------- | --------------------------------------------- | ---- |
| TypeBox                            | https://github.com/sinclairzx81/typebox            | TypeScript DSL -> TypeScript Types, JSON Schema |
| ts-runtime                         | https://github.com/fabiandev/ts-runtime            | TypeScript Types -> Runtime Type Validator |
| typescript-json-schema             | https://github.com/YousefED/typescript-json-schema | TypeScript Types -> JSON Schema |
| Ajv: Another JSON Schema Validator | https://github.com/ajv-validator/ajv               | JSON Schema Validator |

## その他

| 名前   | リポジトリ                      | 備考 |
| -------------- | --------------------------------------------- | ---- |
| GPU.js         | https://github.com/gpujs/gpu.js               | |
| Parallel.js    | https://github.com/parallel-js/parallel.js    | |
| Rough Notation | https://github.com/rough-stuff/rough-notation | |
| lz-string      | https://github.com/pieroxy/lz-string          | 高速なテキスト圧縮 `compressToUTF16()`<br> https://pieroxy.net/blog/pages/lz-string/demo.html |
| Moji.js        | https://github.com/niwaringo/moji             | 半角全角変換ライブラリ |
| YubinBango     | https://github.com/yubinbango/yubinbango-data | 郵便番号 → 住所データ |
| Chrome Network Log | chrome://net-export/ | |
