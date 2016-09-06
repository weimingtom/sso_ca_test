Testing How to write cookie to CA server domain and read from CA server domain    

1. For Windows, Run, input 'drivers'

2. Edit etc\hosts, append these lines:

127.0.0.1 www.app1.com
127.0.0.1 www.app2.com
127.0.0.1 www.ca.com

3. Browse pages:

http://www.app1.com:81/get.php
http://www.app1.com:81/login_ca.php
http://www.app1.com:81/get.php
http://www.app1.com:81/index.php
http://www.app2.com:81/get.php
http://www.app2.com:81/index.php

4. see:
http://www.jb51.net/article/40845.htm
http://yuanrufeng.cn/post/247
