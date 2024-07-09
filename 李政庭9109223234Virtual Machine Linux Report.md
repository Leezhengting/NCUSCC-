# Virtual Machine Linux Report

计算机238班 李政庭

---

# Experimental requirement

![image-20240709192908580](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709192908580.png)

# Experimental Step

## 1.Install CentOS

Firstly, I installed the CentOS 7 from [[Index of /centos-vault/7.6.1810/isos/x86_64/ | 清华大学开源软件镜像站 | Tsinghua Open Source Mirror](https://mirrors.tuna.tsinghua.edu.cn/centos-vault/7.6.1810/isos/x86_64/)] . Then i chose `CentOs-7-x86_64-DVD-1810.ios` to install.

![image-20240709194426978](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709194426978.png)

Secondly, I installed VMware WorkStation Pro 16 from[[下载 VMware Workstation Pro | CN](https://www.vmware.com/content/vmware/vmware-published-sites/cn/products/workstation-pro/workstation-pro-evaluation.html.html.html)].

![image-20240709194934899](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709194934899.png)

Then I started to build a virtual machine and configured the environment. The key steps as the follow pictures:

1. 

![image-20240709195634337](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709195634337.png)

2. 

![image-20240709200413262](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709200413262.png)

3. 

![image-20240709200441263](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709200441263.png)

4. 

![image-20240709200129556](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709200129556.png)

5. 

![image-20240709200507919](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709200507919.png)

6. 

![image-20240709200241608](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709200241608.png)

7. 

![image-20240709200719169](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709200719169.png)



+ 7. In this part, I should select the file i downloaded from `CentOs-7-x86_64-DVD-1810.ios` as the IOS image file.

![image-20240709201159928](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709201159928.png)

8. **Next,start my virtual machine.**

![image-20240709202046135](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709202046135.png) 

+ 9. **In this part , click the`software choose` . The choice is as the follow picture:**
+ ![image-20240709202342794](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709202342794.png)

+ ==The `development tools`  contains  `gcc`==

10. **configure the download position**

![image-20240709203012117](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709203012117.png)

![image-20240709204040353](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709204040353.png)

![image-20240709203830817](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709203830817.png)

![image-20240709203846025](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709203846025.png)

![image-20240709203901781](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709203901781.png)

11. Set the Internet

![image-20240709204225064](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709204225064.png)

![image-20240709205422392](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709205422392.png)

**Difficulties that I met**: This is my first time to learn some knowledge about virtual machine and Linux Operate System. So i don't have any experience about these things. To solve this problem, I read some blogs from CSDN and watched some related videos about Linux. After I have a holistic concept about Linux and the history of Linux, I  started to download virtual machine software and CentOS file. Then I configured the basic parameters follow the blogs. In a nutshell, the whole process of exploration is an enhancement of my  ability of retrieving information.

## configure compile environment



![image-20240709211951836](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709211951836.png)

+ Because I already have chose the `development tools` before, so the system already have `g++` and `gcc`.

![image-20240709212025172](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709212025172.png)

![image-20240709212836096](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709212836096.png)

## Use the command line to write C++ program

+ Open the terminal and input`vim Test.cpp` then i can start to code.

	![image-20240709213705624](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709213705624.png)

	**The file is indeed exist.**

	![image-20240709214542023](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709214542023.png)

+ **input`g++ -o name filename.cpp` to compile the file and input`./name` to run my program.**

![image-20240709214226469](李政庭9109223234Virtual Machine Linux Report.assets/image-20240709214226469.png)

**Difficulties that I met**: Although i know how to make a C++ program, it is my first time to use vim. So i have no idea how to use it. So i read some blogs about vim. knowing that vim has three modes: Command Mode, Insert Mode and Last Line Mode. Actually, it is not difficult to handle it after few practice.Therefore,this part is relative easy to accomplish.

### Send to github

I have already put this file to my github