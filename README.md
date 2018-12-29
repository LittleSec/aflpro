
# Specification based Stateful Protocol Greybox Fuzzing #
 

### Install ###
* Prerequistie
>>
    sudo apt-get install libjson-c-dev libjson0-dev libgtop2-dev

* Configeration for network delay
>>
    sudo  vim /etc/sysctl.conf
    add following:
       net.ipv4.tcp_timestamps = 1
       net.ipv4.tcp_tw_reuse = 1
    sudo /sbin/sysctl -p
    sudo reboot

* Setup the aflpro
>>
    make
    sudo make install
    
### see more
[lab report](./实验报告.md)
