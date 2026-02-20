# aa-panel-problem fixed

FINAL FIX (SAFE & CORRECT)
🎯 Goal

Port 80/443 → শুধু Nginx
Apache / OpenLiteSpeed → পুরোপুরি OFF

1.

```
sudo systemctl stop apache2 2>/dev/null
sudo systemctl disable apache2 2>/dev/null
```
2.
```
sudo systemctl stop httpd
sudo systemctl disable httpd
```
3.
```
sudo systemctl stop lsws
sudo systemctl disable lsws
```
4.
```
bt restart
```
aaPanel Internal Address: pa*l.plxbd.baby/admin

username: bbdyeayo

password: 080b4622
