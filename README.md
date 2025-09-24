# Clash-
要想DNS防止泄露，再yaml文件的最后面添加上：
- - GEOIP,CN,DIRECT,no-resolve
- 有时GEOIP会改为“直连”，注意区别
