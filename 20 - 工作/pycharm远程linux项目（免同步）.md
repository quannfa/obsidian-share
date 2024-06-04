---  
share: true  
---  
  
  
# linux通过samba共享文件夹  
  
sudo vi /etc/samba/smb.conf  
  
  
sudo service smbd restart  
  
# windows映射网络驱动器  
  
在linux的IP地址下找到要共享的文件夹，创建映射网络驱动器  
  
创建后的网络驱动器  
  
  
# pycharm ssh解释器  
  
SSH链接  
![](../assets/Pasted%20image%2020240603161241.png)  
  
选择远程目录并取消同步  
![](../assets/Pasted%20image%2020240603161352.png)  
  
  
可以直接打开路径  
![](../assets/Pasted%20image%2020240604170946.png)  
  
如果使用conda，无法自动进入虚拟环境，使用sh：  
![](../assets/Pasted%20image%2020240604171112.png)