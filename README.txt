Hello everybody !!

How to Fix Kali Linux Slow Update Speed [Fix ] 2018.1

Steps: 1. Open terminal 
Type : leafpad /etc/apt/sources.list 

2. Remove everything and paste these lines 

deb https://mirrors.ocf.berkeley.edu/kali kali-rolling main contrib non-free 
#For source package access, uncomment the following line 
#deb-src https://mirrors.ocf.berkeley.edu/kali kali-rolling main contrib non-free 

3. Now enter : apt-get update && apt-get dist-upgrade

This is real work in Kali Linux 2018-1 ( Testing Finish )!

Update Time 4.10.2018 