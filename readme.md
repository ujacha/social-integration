local test profiles
```
local-ssl,local,h2,demo
```


Create Key-Store

```
# keytool -genkey -alias local-ssl -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore local-keystore -validity 3650
```

allow ssl local
```
chrome://flags/#allow-insecure-localhost
```

Developer Site

* KAKAO
    * https://developers.kakao.com/console/app

* NAVER
    * https://developers.naver.com/apps/#/list

* GOOGLE
    * https://console.developers.google.com/apis/
