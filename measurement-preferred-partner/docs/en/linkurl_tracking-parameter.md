# [Display Ads]Parameters for Destination URL
Some parameters are available for Destination URL. Parameters are replaced dynamically.<br>
Tracking Parameters for Display Ads API are as follows.<br>
<br>

Parameter | Description | URL Format   
----------- | ----------------- | ----------------
creative | Returns Ad ID. | http://xxxxx.co.jp/?creative={creative}
media | Returns Media ID.| http://xxxxx.co.jp/?media={media}
campaignid | Returns Campaign ID.| http://xxxxx.co.jp/?campaignid={campaignid}
adgroupid | Returns Ad Group ID.| http://xxxxx.co.jp/?adgroupid={adgroupid}
account | Returns Account ID.| http://www.example.com/?account={account}
device | Returns the device type.<br>Returns the elements as follows:<br> -DESKTOP<br> -WAP_MOBILE<br> -SMARTPHONE<br> -TABLET<br>* Returns NONE, if cannot be identified. | http://xxxxx.co.jp/?device={device}
os | Returns the OS type.<br>Returns the elements as follows:<br> -IOS<br> -ANDROID<br>* Returns NONE, if cannot be identified. | http://xxxxx.co.jp/?os={os}
isApp | Returns the App type.<br>Tracks if delivered to iOS apps and/or Android apps<br> - true: delivered to iOS apps and/or Android apps<br> - false: not delivered to iOS apps or Android apps | http://xxxxx.co.jp/?isApp={isApp}
ifaSha1 | Returns Hash (sha1) of Ad identifier.<br>Tracks Hash (sha1) of IFA (Ad identifier).<br> - For iOS: IDFA<br> - For Android OS: AdvertisingID| http://xxxxx.co.jp/?ifaSha1={ifaSha1}
ifaMd5 | Returns Hash (md5) of Ad identifier.<br>Tracks Hash (md5) of IFA (Ad identifier).<br> - For iOS: IDFA<br> - For Android OS: AdvertisingID| http://xxxxx.co.jp/?ifaMd5={ifaMd5}
ifa | Returns Ad identifier.<br>Tracks IFA (Ad identifier).<br> - For iOS: IDFA<br> - For Android OS: AdvertisingID| http://xxxxx.co.jp/?ifa={ifa}
ifmobile:[xxxxx] | For the access from smartphones, a unique value (xxxxx) will be added. This option allow you to convert the URL to the one for smartphones and also you can add a parameter. |  https://{ifmobile:m.}xxxxx.co.jp
ifnotmobile:[xxxxx] | For the access from PC or tablet, a unique value (xxxxx) will be added.This option allow you to convert the URL to the one for PC/tablet and also you can add a parameter. | https://{ifnotmobile:www.}xxxxx.co.jp
siteid| Returns Inventory ID.| http://xxxxx.co.jp/?siteid={siteid}
`__timestamp__` | Parameters for Cash Busting. | http://xxxxx.co.jp/?cb=__timestamp__

## Notes
These parameters are available for Display Ads.
