# linux_malware_sandbox
using qemu to dynamic analysis malware

* make sure your network already used VPN before your start sandbox.




# reference
Build image of arm architecture on x86 machine
  https://zhuanlan.zhihu.com/p/106054643
  
# note
docker run command
'''bash
  docker run -it -v $PWD/output:/output/ -v $PWD/virus:/sample/ -v $PWD/exec_script:/exec_script --cap-add=NET_RAW --cap-add=NET_ADMIN imagename
'''