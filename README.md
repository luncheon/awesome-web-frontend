# Awesome Web Frontend

My curated list of frontend libraries.


## DOM Renderer

- Solid  
  https://github.com/ryansolid/solid
- ~~Vidact~~  
  ~~https://mohebifar.github.io/vidact/
- lit-html  
  https://lit-html.polymer-project.org/
- Preact  
  https://preactjs.com/
- incremental-dom  
  http://google.github.io/incremental-dom/
  - babel-plugin-transform-incremental-dom  
    https://github.com/jridgewell/babel-plugin-transform-incremental-dom


## State

- MobX  
  https://mobx.js.org/
- Immer  
  https://immerjs.github.io/immer/


## Memoization

- memoize-one  
  https://github.com/alexreardon/memoize-one/
- Reselect  
  https://github.com/reduxjs/reselect
  - 全状態を単一オブジェクトに詰め込んでいる場合に限り有効。


## CSS in JS

- Linaria  
  https://github.com/callstack/linaria
- style9  
  https://github.com/johanholmerin/style9
- Compiled  
  https://compiledcssinjs.com/


## Form

### Validation

- Vest  
  https://github.com/ealush/vest


## UI Parts

### Tooltip

- Balloon.css  
  https://kazzkiq.github.io/balloon.css/
  - CSS カスタムプロパティが利用されている（そのままでは IE 11 で動かなそう）。
- Hint.css  
  https://kushagra.dev/lab/hint/
  - `[class*="hint--"]` のようなセレクターが使われている。古いベンダープレフィックス付きの `-moz-transform` や `-moz-transition` が使われていて冗長。
- Tlite  
  https://chrisdavies.github.io/tlite/
  - `title` 属性を見てくれるので既存コードへの適用がラク。
- html5tooltips.js  
  http://ytiurin.github.io/html5tooltipsjs/
  - 表示アニメーションのプリセットがいくつかあっておもしろい（ただし実際のプロダクトではツールチップが目を引いちゃダメ）。
- ~~Tootik~~  
  ~~https://eliortabeka.github.io/tootik/~~
  - ツールチップ本体表示後、遅れて吹き出しの尻尾が出てくる。この挙動が気になるので使えない。
- ~~Microtip~~  
  ~~https://github.com/ghosh/microtip~~
  - 対象要素に `role="tooltip"` を付与しなければならない奇妙仕様。
- ~~Tippy.js~~  
  ~~https://atomiks.github.io/tippyjs/~~
  - Popper ベース。重い。


### Toast

- Toastify  
  https://apvarun.github.io/toastify-js/
- toastedjs  
  https://shakee93.github.io/toastedjs/

### Progress Indicator

- topbar  
  http://buunguyen.github.io/topbar/
- Rsup Progress  
  https://skt-t1-byungi.github.io/rsup-progress/
- ~~Pace.js~~  
  ~~https://github.hubspot.com/pace/docs/welcome/~~
  - XHR 時代は何も考えずに使えて非常に便利だった。既知のメモリリークがある。今後メンテナンスしないと明言されている。

### Modal

- html-native-modal  
  https://github.com/luncheon/html-native-modal
- Modal Vanilla  
  https://github.com/KaneCohen/modal-vanilla
- ~~Micromodal.js~~  
  ~~https://micromodal.now.sh/~~
  - デモは良さそうだけど動かし方がよく分からなかった。
- ~~tingle.js~~  
  ~~https://tingle.robinparisi.com/~~
  - 背景が全く見えなくなる。閉じるときアニメーションがない。
- ~~A11y Dialog~~  
  ~~http://edenspiekermann.github.io/a11y-dialog/~~
  - マークアップが非常に煩雑。閉じるときアニメーションがない。

### Tabs

- Tabby  
  https://github.com/cferdinandi/tabby

### Carousel

- Embla Carousel  
  https://davidcetinkaya.github.io/embla-carousel/

## Canvas

- Fabric.js  
  http://fabricjs.com/
- Two.js  
  https://two.js.org/


## Data Visualization

### Data Table

- Grid.js  
  https://gridjs.io/
- Cheetah Grid (rendering the table on canvas)  
  https://future-architect.github.io/cheetah-grid/
- Clusterize.js (virtual scroll library)  
  https://clusterize.js.org/


### Chart

- Chart.js  
  https://www.chartjs.org/
- APEXCHARTS.JS  
  https://apexcharts.com/
- C3.js (requires D3.js)  
  https://c3js.org/
- billboard.js (fork of C3.js)  
  https://naver.github.io/billboard.js/
- morris.js (requires jQuery)  
  https://morrisjs.github.io/morris.js/
- Flot (requires jQuery)  
  https://www.flotcharts.org/
- Plotly  
  https://plotly.com/javascript/
- roughViz.js  
  https://github.com/jwilber/roughViz


### Mini Chart

- Peity (requires jQuery)  
  http://benpickles.github.io/peity/
- Sparklines (requires jQuery)  
  https://omnipotent.net/jquery.sparkline/


## CSS Framework

### Material Design

- MUI  
  https://www.muicss.com/
- ~~Materialize~~  
  ~~https://materializecss.com/~~
  - 重い。


## Icons

- Material Design Icons  
  https://materialdesignicons.com/
- Font Awesome  
  https://fontawesome.com/
- Icons8 Line Awesome  
  https://github.com/icons8/line-awesome  
- Icons8 Flat Color Icons  
  https://github.com/icons8/flat-color-icons  
- Iconicons  
  https://ionicons.com/
- Feather  
  https://feathericons.com/
- css.gg  
  https://css.gg/
- Eva Icons  
  https://akveo.github.io/eva-icons
- Remix Icon  
  https://remixicon.com/
- Ikonate  
  https://ikonate.com/
- Vue Unicons  
  https://antonreshetov.github.io/vue-unicons/
- Tabler Icons  
  https://tablericons.com/

### Brand Icons

- Simple Icons  
  https://simpleicons.org/  


## Presentation

- reveal.js  
  https://revealjs.com/
- Bespoke.js  
  http://markdalgleish.com/projects/bespoke.js/


## Others

- GPU.js  
  https://github.com/gpujs/gpu.js
