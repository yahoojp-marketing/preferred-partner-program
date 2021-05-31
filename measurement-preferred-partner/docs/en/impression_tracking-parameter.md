# [Display Ads]Parameters for impression tracking
By setting the impression beacon URL with parameters in the ads of your advertisers and agencies, you can send requests to the impression tracking URL when delivering the ads.

Tracking Parameters for Display Ads API are as follows.<br>
<br>

Parameter | Description | URL Format   
----------- | ----------------- | ----------------
creative | Returns Ad ID. | http://www.example.com/?creative={creative}
media | Returns Media ID.| http://www.example.com/?media={media}
campaignid | Returns Campaign ID.| http://www.example.com/?campaignid={campaignid}
adgroupid | Returns Ad Group ID.| http://www.example.com/?adgroupid={adgroupid}
account | Returns Account ID.| http://www.example.com/?account={account}
device | Returns the device type.<br>Returns the elements as follows:<br> -DESKTOP<br> -WAP_MOBILE<br> -SMARTPHONE<br> -TABLET<br>* Returns NONE, if cannot be identified. | http://www.example.com/?device={device}
os | Returns the OS type.<br>Returns the elements as follows:<br> -IOS<br> -ANDROID<br>* Returns NONE, if cannot be identified. | http://www.example.com/?os={os}
isApp | Returns the App type.<br>Tracks if delivered to iOS apps and/or Android apps<br> - true: delivered to iOS apps and/or Android apps<br> - false: not delivered to iOS apps or Android apps | http://www.example.com/?isApp={isApp}
ifaSha1 | Returns Hash (sha1) of Ad identifier.<br>Tracks Hash (sha1) of IFA (Ad identifier).<br> - For iOS: IDFA<br> - For Android OS: AdvertisingID| http://www.example.com/?ifaSha1={ifaSha1}
ifaMd5 | Returns Hash (md5) of Ad identifier.<br>Tracks Hash (md5) of IFA (Ad identifier).<br> - For iOS: IDFA<br> - For Android OS: AdvertisingID| http://www.example.com/?ifaMd5={ifaMd5}
ifa | Returns Ad identifier.<br>Tracks IFA (Ad identifier).<br> - For iOS: IDFA<br> - For Android OS: AdvertisingID| http://www.example.com/?ifa={ifa}
ifmobile:[xxxxx] | For the access from smartphones, a unique value (xxxxx) will be added. This option allow you to convert the URL to the one for smartphones and also you can add a parameter. |  https://{ifmobile:m.}xxxxx.co.jp
ifnotmobile:[xxxxx] | For the access from PC or tablet, a unique value (xxxxx) will be added.This option allow you to convert the URL to the one for PC/tablet and also you can add a parameter. | https://{ifnotmobile:www.}xxxxx.co.jp
siteid| Returns Inventory ID.| http://xxxxx.co.jp/?siteid={siteid}
`__timestamp__` | Parameters for Cash Busting. | http://www.example.com/?cb=__timestamp__
useragent | Returns device user agent. | http://xxxxx.co.jp/?useragent={useragent}
ipaddress | Returns device IP address. | http://xxxxx.co.jp/?ipaddress={ipaddress}
language | Returns devive language setting and locale. | http://xxxxx.co.jp/?language={language}
deviceAppType | You can identify the ad placement "App" or "Web."<br>Returns the elements as follows:<br> -web<br> -app<br>*Setting the campaign goal "app promotion" is available on Display Ads (Auction).<br>*Available only when using the tracking tool linked to Display Ads. | http://xxxxx.co.jp/?deviceAppType={deviceAppType}


## Notes
These parameters are available for Display Ads.
