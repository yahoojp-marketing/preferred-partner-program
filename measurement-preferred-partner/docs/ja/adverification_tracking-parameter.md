# [ディスプレイ広告 ]アドベリフィケーション計測用スクリプトタグ利用可能パラメータ一覧
広告主・代理店の任意の広告にアドベリフィケーション計測用スクリプトタグを設定することで、広告配信時に当該jsタグの値が変換された状態でタグが書き出されます。<br>
アドベリフィケーション計測用jsに付与可能なパラメータは、以下のとおりです。<br>
注意：広告入稿時は「第三者測定スクリプトタグsrc属性url」という名称で入稿する項目です。<br>



パラメータ | 概要 | URLフォーマット   
----------- | ----------------- | ----------------
creative | 広告IDです。 | http://xxxxx.co.jp/example.js?creative={creative}
media | メディアIDです。|http://xxxxx.co.jp/example.js?media={media}
campaignid | キャンペーンIDです。| http://xxxxx.co.jp/example.js?campaignid={campaignid}
adgroupid | 広告グループIDです。| http://xxxxx.co.jp/example.js?adgroupid={adgroupid}
account| アカウントIDです。  | http://xxxxx.co.jp/example.js?account={account}
device | デバイスの種類です。<br>以下の内容が返却されます。<br>・DESKTOP<br>・WAP_MOBILE<br>・SMARTPHONE<br>・TABLET<br>※識別できない場合は、NONEとなります。 | http://xxxxx.co.jp/example.js?device={device}
os | OSの種類です。<br>以下の内容が返却されます。<br>・IOS<br>・ANDROID<br>※識別できない場合は、NONEとなります。 | http://xxxxx.co.jp/example.js?os={os}
isApp | iOSアプリ、Androidアプリに配信されたかを表示します。<br>・iOSアプリ、Androidアプリの場合：true<br>・上記以外の場合：false | http://xxxxx.co.jp/example.js?isApp={isApp}
ifmobile:[任意の値] | スマートフォンからアクセスした際に、任意の値を付加します。これにより、スマートフォン向けURLへの変換やパラメータの追加などが可能です。  |  https://{ifmobile:m.}xxxxx.co.jp
ifnotmobile:[任意の値]} | PC・タブレットなどスマートフォン以外の端末からアクセスした際に、任意の値を付加します。これにより、PC・タブレット向けURLへの変換やパラメータの追加などが可能です。 | https://{ifnotmobile:www.}xxxxx.co.jp


## 補足
上記パラメータはディスプレイ広告で利用可能です。
