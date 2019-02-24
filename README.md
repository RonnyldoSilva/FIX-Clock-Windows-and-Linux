# FIX Windows and Linux Clock

Evitando que o Linux bagunce o horário do Windows em sistemas dual-boot

```
sudo timedatectl set-local-rtc 1 --adjust-system-clock
```
