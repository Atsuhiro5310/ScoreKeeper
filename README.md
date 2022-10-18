# 概要
１対１で得点を争う際の得点表として使うことができます。今回は卓球の試合を想定して得点表を作りました。

# 機能
- 何点先取かを決める
- １点ずつ得点を加算する
- 得点をリセットする（何点先取かを変えた時も）

# なぜ作ったか
Udemyの作成課題だったため（DOMイベントについての復習）

# 使用した言語と学習のポイント
- HTML
 - querySelectorで連携するためにidの登録をしておく
 - selectの復習
 - Bulmaを使ってみる
  * class="column is-half is-offset-one quarter" 中心に
  * class="title is-1" 大きめな文字
  * class="button is-primary" 色の選択
  * div class="select is-rounded" セレクトのスタイル
  * figure class="image is-2by1"　横２：縦１の画像を挿入
            img src="hogehoge"　画像のソースを入れる
- JavaScript
 - addEventListenerでイベントを追加する（click, change）
 - textContentの使用
 - thisの確認（thisでもらうのはString）⇦typeofで確認
 - parseInt()でnumberにする
 - classList.add()でクラスを追加（classList.remove()でクラスを削除）
 - Bulmaを使ってみる
  * class="has-text-success" 文字の色の選択
  * button.disabled ボタンを無効化する属性を持つ
 - リファクタをする　（オブジェクトを作った上で関数を作る、ループを使う）
