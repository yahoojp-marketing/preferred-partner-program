# インプレッションビーコン利用可能パラメータ一覧
広告主・代理店の任意の広告にインプレッションビーコンURLを設定することで、広告配信時に当該ビーコンURLへリクエストを飛ばすことが可能です。<br>
インプレッションビーコンURLに付与可能なパラメーターは、以下のとおりです。<br>



パラメータ | 概要 | URLフォーマット   
----------- | ----------------- | ----------------
creative | 広告IDです。 | http://www.example.com/?creative={creative}
media | メディアIDです。|http://www.example.com/?media={media}
campaignid | キャンペーンIDです。| http://www.example.com/?campaignid={campaignid}
adgroupid | 広告グループIDです。| http://www.example.com/?adgroupid={adgroupid}
device | デバイスの種類です。<br>以下の内容が返却されます。<br>・DESKTOP<br>・WAP_MOBILE<br>・SMARTPHONE<br>・TABLET<br>※識別できない場合は、NONEとなります。 | http://www.example.com/?device={device}
os | OSの種類です。<br>以下の内容が返却されます。<br>・IOS<br>・ANDROID<br>※識別できない場合は、NONEとなります。 | http://www.example.com/?os={os}
isApp | iOSアプリ、Androidアプリに配信されたかを表示します。<br>・iOSアプリ、Androidアプリの場合：true<br>・上記以外の場合：false | http://www.example.com/?isApp={isApp}
ifaSha1 | IFA（広告識別子）のハッシュ値（sha1）です。<br>・iOSの場合：IDFA<br>・Android OSの場合：AdvertisingID|http://www.example.com/?ifaSha1={ifaSha1}
ifaMd5 | IFA（広告識別子）のハッシュ値（md5）です。<br>・iOSの場合：IDFA<br>・Android OSの場合：AdvertisingID|http://www.example.com/?ifaMd5={ifaMd5}
ifa | IFA（広告識別子）です。<br>・iOSの場合：IDFA<br>・Android OSの場合：AdvertisingID|http://www.example.com/?ifa={ifa}
__timestamp__ | キャッシュバスティング用のパラメータです。 | http://www.example.com/?cb=__timestamp__
