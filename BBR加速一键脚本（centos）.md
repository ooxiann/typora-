==原文地址==

http://loonlog.com/2019/10/12/v2ray-bbr/

**一键脚本（仅CentOS）：**

wget "https://github.com/cx9208/bbrplus/raw/master/ok_bbrplus_centos.sh" && chmod +x ok_bbrplus_centos.sh && ./ok_bbrplus_centos.sh

- 安装后，执行uname -r，显示4.14.129-bbrplus则切换内核成功

- 执行lsmod | grep bbr，显示有bbrplus则开启成功

  

![image-20211122154627482](/Users/a10.11.5/Library/Application Support/typora-user-images/image-20211122154627482.png)

![image-20211122154701489](/Users/a10.11.5/Library/Application Support/typora-user-images/image-20211122154701489.png)

