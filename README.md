# Stop the Bokettch for baserCMS

## これは何?

サイトの公開状態が「メンテナンス中」のとき、画面上部のツールバーに通知メッセージを表示するプラグインです。

管理画面にログインしていると、サイトの公開状態にかかわらずフロント側（＝運用中のウェブサイト）を見ることができます。そのため、うっかり「メンテナンス中にしたまま放置」という状況が起こりかねません。そうした うっかりミス＝**ぼけっち** をなくしたいと考えて作ったプラグインです。

プラグイン名は、クローラ受け入れの諾否を通知する WordPress プラグイン『[Stop the Bokettch](https://wordpress.org/plugins/stop-the-bokettch/)』に由来しています。

## インストール方法

git clone または ZIP ファイルをダウンロードして /app/Plugin ディレクトリ内に配置してください。ZIP ファイルの場合 StopTheBokettch-master というフォルダ名で展開されるので、あらかじめ StopTheBokettch とリネームする必要があります。

インストール後、管理画面の [プラグイン管理] で『Stop the Bokettch for baserCMS』プラグインを有効化してください。

## 使い方

サイトの公開状態が「メンテナンス中」のとき、画面上部のツールバーに「サイトメンテナンス中」の通知メッセージが表示されます。

公開状態は、管理画面の [システム設定] － [サイト基本設定] にある「公開状態」セレクトボックスで設定できます。

## 留意事項

通知メッセージは、デフォルトのツールバーエレメント（ /lib/Baser/View/Elements/admin/toolbar.php ）の出力を一部置換して出力しています。ツールバーにカスタマイズを加えている場合、通知メッセージの表示がうまくいかないことがありますのでご注意ください。

## 謝辞

『Stop the Bokettch』の名を拝借するにあたり、プラグイン作者の [@jim0912](https://twitter.com/jim0912) さん、ぼけっちの生みの親 [@Webourgeon_com](https://twitter.com/Webourgeon_com) さんのご快諾をたまわりました。ありがとうございます。

## 更新履歴

* 0.1.1（ 2015-02-06 ）
 * コーディング規約に沿ってリファクタリング
* 0.1.0（ 2015-02-06 ）
 * 公開