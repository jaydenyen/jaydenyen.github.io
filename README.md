# Jayden Yen's Website

利用 init_replit 指令安裝所需 Python 模組

chmod u+x init_replit

./init_replit

On Replit:

for cmsimde: pip install flask flask_cors bs4 lxml pelican markdown gevent

for IPv6 only Ubuntu:

.ssh 目錄中的 config, 將 SSH session 名稱設為 github.com:

Host github.com
User git
Hostname github.com
ProxyCommand /usr/bin/ncat --proxy p4.cycu.org:3128 --proxy-type http %h %p

for Replit:

.ssh 目錄中的 config, 將 SSH session 名稱設為 github.com:

Host github.com
User git
Hostname github.co
#since Replit works for IPv4, therefore no ProxyCommand setting needed
#ProxyCommand /usr/bin/ncat --proxy p4.cycu.org:3128 --proxy-type http %h %p
