# PyLocalIP

Overview
------------
Get Linux system local IP with system call `ioctl` using python!
Safty, fast and flexible

Installation
------------
pip install PyLocalIP

Usage
------------
```
import PyLocalIP
local_ip = PyLocalIP.get_local_ip("eth0")
#or default with eth0
local_ip = PyLocalIP.get_local_ip()
```
