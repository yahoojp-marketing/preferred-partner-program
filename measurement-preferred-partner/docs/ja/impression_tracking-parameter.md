# [ディスプレイ広告]インプレッションビーコン利用可能パラメータ一覧
広告主・代理店の任意の広告にインプレッションビーコンURLを設定することで、広告配信時に当該ビーコンURLへリクエストを飛ばすことが可能です。<br>
インプレッションビーコンURLに付与可能なパラメーターは、以下のとおりです。<br>



パラメータ | 概要 | URLフォーマット   
----------- | ----------------- | ----------------
creative | 広告IDです。 | http://xxxxx.co.jp/?creative={creative}
media | メディアIDです。|http://xxxxx.co.jp/?media={media}
campaignid | キャンペーンIDです。| http://xxxxx.co.jp/?campaignid={campaignid}
adgroupid | 広告グループIDです。| http://xxxxx.co.jp/?adgroupid={adgroupid}
account| アカウントIDです。  | http://xxxxx.co.jp/?account={account}
device | デバイスの種類です。<br>以下の内容が返却されます。<br>・DESKTOP<br>・WAP_MOBILE<br>・SMARTPHONE<br>・TABLET<br>※識別できない場合は、NONEとなります。 | http://xxxxx.co.jp/?device={device}
os | OSの種類です。<br>以下の内容が返却されます。<br>・IOS<br>・ANDROID<br>※識別できない場合は、NONEとなります。 | http://xxxxx.co.jp/?os={os}
isApp | iOSアプリ、Androidアプリに配信されたかを表示します。<br>・iOSアプリ、Androidアプリの場合：true<br>・上記以外の場合：false | http://xxxxx.co.jp/?isApp={isApp}
ifaSha1 | IFA（広告識別子）のハッシュ値（sha1）です。<br>・iOSの場合：IDFA<br>・Android OSの場合：AdvertisingID|http://xxxxx.co.jp/?ifaSha1={ifaSha1}
ifaMd5 | IFA（広告識別子）のハッシュ値（md5）です。<br>・iOSの場合：IDFA<br>・Android OSの場合：AdvertisingID|http://xxxxx.co.jp/?ifaMd5={ifaMd5}
ifa | IFA（広告識別子）です。<br>・iOSの場合：IDFA<br>・Android OSの場合：AdvertisingID|http://xxxxx.co.jp/?ifa={ifa}
ifmobile:[任意の値] | スマートフォンからアクセスした際に、任意の値を付加します。これにより、スマートフォン向けURLへの変換やパラメータの追加などが可能です。  |  https://{ifmobile:m.}xxxxx.co.jp
ifnotmobile:[任意の値]} | PC・タブレットなどスマートフォン以外の端末からアクセスした際に、任意の値を付加します。これにより、PC・タブレット向けURLへの変換やパラメータの追加などが可能です。 | https://{ifnotmobile:www.}xxxxx.co.jp
siteid| 広告枠IDです。| http://xxxxx.co.jp/?siteid={siteid}
`__timestamp__` | キャッシュバスティング用のパラメータです。 | http://xxxxx.co.jp/?cb=__timestamp__
useragent | 端末のユーザーエージェントです。 | http://xxxxx.co.jp/?useragent={useragent}
ipaddress | 端末のIPアドレスです。 | http://xxxxx.co.jp/?ipaddress={ipaddress}
language | 端末の言語設定です。 | http://xxxxx.co.jp/?language={language}

## 補足
上記パラメータはディスプレイ広告で利用可能です。
