Testing How to write cookie to other domain  

1. For Windows, Run, input 'drivers'

2. Edit etc\hosts, append these lines:

127.0.0.1 www.app1.com
127.0.0.1 www.app2.com
127.0.0.1 www.ca.com

3. Browse pages:

http://www.ca.com:81/login_app1.php
http://www.app1.com:81/index.php
