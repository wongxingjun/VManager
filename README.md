VManager
========
##Introduction
A simple `LXC`(Linux Container) managing system implemented with Python.
You can download it for personal non-commercial use.
##Environment requirements:
- [LXC-1.0.0-alpha](https://www.linuxcontainers.org)
- [libvirt-0.9.8](http://libvirt.org)
- [python-2.7](http://python.org)
- [web.py-0.37](https://pypi.python.org/pypi/web.py)
- MySQL-5.6

##Tips:
This system is a simple system to manage LXCs in a server. I ran it successfully on my PC with Ubuntu12.04(Recommanded). Due to some bugs in LXC(v1.0.0-alpha) and uncomplete suportting provided by libvirt towards LXC, some advanced functions are not implemented perfectly, such as vCPU number limit and memory limit.
