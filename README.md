# hashtopolis-startup
Hashtopolis Startup Auto

```
cd /hashtopolis && git clone https://github.com/joelqc1/hashtopolis-startup && cd hashtopolis-startup && mv hashtopolis.service /etc/systemd/system && mv hashtopolis_startup.sh /hashtopolis && cd && cd /hashtopolis && chmod +x hashtopolis_startup.sh && apt update && systemctl daemon-reload && systemctl enable hashtopolis.service && systemctl start hashtopolis.service
```
