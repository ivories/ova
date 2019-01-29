# 下载 virtualbox 
    
    Mac : https://download.virtualbox.org/virtualbox/5.1.38/VirtualBox-5.1.38-122592-OSX.dmg
    Win : https://download.virtualbox.org/virtualbox/5.1.38/VirtualBox-5.1.38-122592-Win.exe
   
# 网络安装
    
    Mac : Virtualbox >  5.1.38 点击左上角 "管理" -> "主机网络管理器" -> "创建(C)"
    Mac : Virtualbox <= 5.1.38 点击左上角 "偏好设置" -> "网络" -> "仅主机(Host-Only)网络" -> "添加新NAT网络"
    Win : 安装完毕之后 VirtualBox Host-Only Ethernet Adapter 会自动安装好，无需配置
 
# 导入
    
    导入CoreOS.ova文件即可
    出现网络错误直接忽略，或者关闭再重启
    
# 安装web服务

    i nginx && i php && i mysql && i redis
    s nginx && s php && s mysql && s redis
    
