## 安装freeradius-util: radclient, radeapclient, radtest
``` bash
apt-get install freeradius-utils
```


## 容器内编译 radclient, radeapclient
``` bash
cd /app/third_party/freeradius-3.2.3

make clean

./configure

make

ls /app/third_party/freeradius-3.0.21/build/bin/
dhcpclient  local  map_unit  radattr  radclient  radeapclient  radiusd radmin  radwho  rbmonkey  smbencrypt  unittest
```
