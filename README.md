# software-principle

ソフトウェア関連の法則や原則

個人的な理解をまとめます。

`小さく始めて、必要に応じて機能を実装し、情報は一箇所に集めて、依存に柔軟で、単純なコードに保つ`


## 一覧

|  項目  |  内容  |  備考  |
| ---- | ---- | ---- |
|  単一責任の原則(SRP:single responsibility principle)  |  クラスはたったひとつの役割を持つ、クラスを修正する理由はたったひとつだけ  |  SOLID  |
|  解放閉鎖の原則(OCP:open closed principle)  |  既存のクラスを修正せずに機能を追加する  |  SOLID  |
|  リスコフの置換原則(LSP:liskov substitution principle)  |  インターフェイスを受け取り、インターフェイスで処理する  |  SOLID  |
|  インターフェイス分離の原則(ISP:interface segregation principle)  |  クライアントに必要十分なインターフェイスを用意する  |  SOLID  |
|  依存性逆転の原則(DIP:dependency inversion principle)  |  インターフェイスを用意して外部の実装を注入する  |  SOLID  |
|  最小知識の原則(Principle of Least Knowledge)  |  オブジェクトは他のオブジェクトの内部構造に依存しない、結合度は低く保つ  |  デメテルの法則  |
|  KISS(keep it simple stupid)  |  単純に、簡潔に  |  x  |
|  DRY(dont repeat yourself)  |  情報は一箇所に集める。ただし密結合は避ける。  |  x  |
|  YAGNI(You aren't gonna need it)  |  機能は必要になるまで追加しない  |  x  |
|  Worse is better  |  正しさよりも単純さを優先する  |  ニュージャージースタイル  |
|  ブルックスの法則  |  遅れているプロジェクトへの要員追加はプロジェクトをさらに遅くする  |  キャッチアップ、コミュニケーション、タスク分解  |
|  コンウェイの法則  |  システムは設計する組織の構造を映す  |  x  |
|  ホフスタッターの法則  |  いつでも予測以上の時間がかかるものである — ホフスタッターの法則を計算に入れても。  |  x  |
|  驚き最小の原則  |  クライアントの納得度の高い選択肢を選ぶ  |  x  |
|  ボーイスカウトの規則  |  さわる前よりも綺麗にする  |  x  |
|  パーキンソンの法則  |  仕事の量は、完成のために与えられた時間をすべて満たすまで膨張する、支出の額は、収入の額に達するまで膨張する  |  x  |
|  ハインリッヒの法則  |  一件の大きな事故・災害の裏には、29件の軽微な事故・災害、そして300件のヒヤリ・ハット  |  ヒヤリ・ハットの段階で対処  |
|  ヒックの法則  |  選択肢は少ない方が、決断は早い  |  x  |
|  ポステルの法則  |  送信するものに関しては厳密に、受信するものに関しては寛容に  |  x  |
|  パレートの法則  |  全体の数値の大部分は、全体を構成するうちの一部の要素が生み出している  |  x  |
|  ピーターの法則  |  人間は能力の極限まで出世する、そして無能な中間管理職になる  |  x  |
|  オッカムの剃刀  |  必要十分な情報で説明する  |  x  |


## 参考
- [ソフトウェア原則](http://objectclub.jp/technicaldoc/object-orientation/principle/)
- [開発者が知っておくべきSOLIDの原則](https://postd.cc/solid-principles-every-developer-should-know/)
- [何かのときにすっと出したい、プログラミングに関する法則・原則一覧](https://qiita.com/hirokidaichi/items/d6c473d8011bd9330e63)
- [人名を冠したソフトウェア開発の19の法則](https://www.yamdas.org/column/technique/19laws.html)
- [Martin Fowler's Bliki (ja)](https://bliki-ja.github.io)
- [AggregateRoot – 集約](https://nrslib.com/aggregateroot/)
