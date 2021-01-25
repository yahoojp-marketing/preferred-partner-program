# [Display Ads]Parameters for adverification javascript tag
By setting the adverification tracking js in the ads of your advertisers and agencies, the tags will have converted values when delivering ads. Available parameters for adverification tracking js are as follows.
Note: This setting is for the item “Third-party script tag src attribute URL” when creating ads.

<br>

Parameter | Description | URL Format   
----------- | ----------------- | ----------------
creative | Returns Ad ID. | http://www.example.com/example.js?creative={creative}
media | Returns Media ID.| http://www.example.com/example.js?media={media}
campaignid | Returns Campaign ID.| http://www.example.com/example.js?campaignid={campaignid}
adgroupid | Returns Ad Group ID.| http://www.example.com/example.js?adgroupid={adgroupid}
account | Returns Account ID.| http://www.example.com/example.js?account={account}
device | Returns the device type.<br>Returns the elements as follows:<br> -DESKTOP<br> -WAP_MOBILE<br> -SMARTPHONE<br> -TABLET<br>* Returns NONE, if cannot be identified. | http://www.example.com/example.js?device={device}
os | Returns the OS type.<br>Returns the elements as follows:<br> -IOS<br> -ANDROID<br>* Returns NONE, if cannot be identified. | http://www.example.com/example.js?os={os}
isApp | Returns the App type.<br>Tracks if delivered to iOS apps and/or Android apps<br> - true: delivered to iOS apps and/or Android apps<br> - false: not delivered to iOS apps or Android apps | http://www.example.com/example.js?isApp={isApp}
ifmobile:[xxxxx] | For the access from smartphones, a unique value (xxxxx) will be added. This option allow you to convert the URL to the one for smartphones and also you can add a parameter. |  https://{ifmobile:m.}xxxxx.co.jp
ifnotmobile:[xxxxx] | For the access from PC or tablet, a unique value (xxxxx) will be added.This option allow you to convert the URL to the one for PC/tablet and also you can add a parameter. | https://{ifnotmobile:www.}xxxxx.co.jp

## Notes
These parameters are available for Display Ads.
