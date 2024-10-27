# 風花雪月ペアシミュレーター

支援をB止めして最後に任意のペアを作る時の手助けをするfletアプリケーションです。

[リンク](https://feth-pairing-simulator.pages.dev)

## Demo

![デモ動画](resource/demo.gif)

## Features

- 現在のメンバーに応じた動的なペア選択。
- ペアの履歴の管理。

## Usage

1. 所属しているキャラクターを選択します。
  「操作」「ルートプリセットで自動選択」「（任意のルート）」を選ぶと、ルート毎のデフォルト加入キャラクターが自動的に選択され、加入不可のキャラクターは未選択になります。
2. ペアを作成します。
   - キャラクター名の頭にある"既"と"未"は、そのキャラクターとのペア履歴の有無を示しています。
   - キャラクター名の横線は、そのキャラクターが既に他のキャラクターとペアであることを示しています。
   - 既に他のキャラクターとペアであるキャラクターをペアに選ぶと、元のペアを解消してペアになります。
3. 「履歴」「保存」ボタンをクリックしてペアを確定し、ストレージに保存します。
  キャラクターの選択内容が保存され、成立しているペアがペア履歴に追加されます。

間違ったペアを記録してしまった場合は、以下の手順で削除できます。

1. 「操作」「全てのペアを解消」ボタンを押す、もしくはペアになっている全てのドロップダウンを手動で「ソロエンド（orエンド無し）」にします。
2. 履歴から削除したいペアを組みます。
3. 「履歴」「ペアを履歴から削除」ボタンを押します。

このプログラムがストレージに作成した保存ファイルを削除するには、「履歴」「全ての履歴を削除」ボタンを押します。

## Note

誰が誰とペアになる、というネタバレを含みます。

## クレジット

<dl>
 <dt>ファイアーエムブレム 風花雪月の権利表記</dt>
  <dd>© 2019 Nintendo / INTELLIGENT SYSTEMS Co-developed by KOEI TECMO GAMES CO., LTD.</dd>
  <dt>キャラクターデータの参考元</dt>
  <dd><a href="https://www.pegasusknight.com/wiki/fe16/">ファイアーエムブレム 風花雪月 攻略Wiki</a></dd>
 <dt>キャラクターの画像</dt>
  <dd>Nintendo Switchのキャプチャ機能を用いて撮影し、トリミングしたものです。
  </dd>
  <dd>※Nintendo Switchは任天堂の商標です。</dd>
</dl>
