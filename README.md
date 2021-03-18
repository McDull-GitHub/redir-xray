# redir-xray(TCP only)
```
iptables -t nat -A PREROUTING -p tcp -j REDIRECT --to-ports 12345
```
