# 鼠标交互概述

###### *version :2.1.1   Update:2019-8-2*

LayaAir 2 Dエンジンでは、2 D表示オブジェクトはマウスイベントを使用しています。作成ロジックは簡単で便利です。LayaAir 3 Dエンジンではこのような機能は実現されておらず、3 D空間はより複雑であり、表示対象は空間の中に奥行きがあり、遠近、積層、裁断、親子などの関係があり、空間は絶えず変化している。このため3 Dエンジンは、衝突器、層と物理放射線検出、衝突情報を用いてマウス判定を行う。
