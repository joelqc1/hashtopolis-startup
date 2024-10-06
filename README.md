# hashtopolis-startup
Hashtopolis Startup Auto

This is service is made, to make hashtopolis agent, wake up once server is restarted automatically. 
```
cd /hashtopolis && git clone https://github.com/joelqc1/hashtopolis-startup && cd hashtopolis-startup && mv hashtopolis.service /etc/systemd/system && mv hashtopolis_startup.sh /hashtopolis && cd && cd /hashtopolis && chmod +x hashtopolis_startup.sh && apt update && systemctl daemon-reload && systemctl enable hashtopolis.service && systemctl start hashtopolis.service && reboot
```
