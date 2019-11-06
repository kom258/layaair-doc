#LayaAir機能紹介

![1](1.png)



LayaAirはエンジンライブラリとLayaAir IDEの二つの核心部分を含んでいます。



##LayaAirエンジンライブラリ機能

LayaAirエンジンは精霊、ベクトル図、テキスト、テキスト、リッチテキスト、ビットマップフォント、アニメーション、骨格、オーディオとビデオ、フィルタ、イベント、ローディング、緩動、時間、ネットワーク、UIシステム、物理システム、TiledMap、prtocolなどのAPIをサポートします。多種のバージョン



**その中:**

-laya.comはコアパッケージであり、表示対象レンダリング、イベント、時間管理、時間軸アニメーション、緩動、メッセージインタラクション、socket、ローカルストレージ、マウスタッチ、音声、ローディング、カラーフィルタ、ビットマップフォントなどをパッケージ化しています。

-laya.webglパッケージにwebglレンダリングパイプラインが封入されています。webglでレンダリングすれば、初期化時にLaya.init（1000,800,laya.webgl.WebGL）を呼び出すことができます。

-laya.ani.jsはアニメーションモジュールであり、swfアニメーション、骨格アニメーションなどが含まれています。

-laya.filter.jsは、外光、影、ぼかし、さらに多くのwebglフィルタを含む。

-laya.html.jsが封入しました。

-laya.ui.jsはUIを作るさまざまなコンポーネントを提供して実現します。

-laya.tilemap.jsは、tileMap解析サポートを提供します。

​



##LayaAir IDE機能

LayaAir IDEは主にコード開発エディタ、可視化エディタ、第三者ツールチェーンサポートツールなどを含みます。

主な機能は以下を含む。

##-コード開発UIエディタ
##-粒子エディタ時間軸アニメーション
##-シーンエディタ3 D対応
##-スクリプト拡張プリセット
##-APPパッケージ化Flashリリース
##-JS混淆と圧縮第三者ツールチェーン変換ツール（SWF、ユニティ3 D、3 DCmax、TiledMap、Spine、竜骨…）