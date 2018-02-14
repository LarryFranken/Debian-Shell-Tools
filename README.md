## 自用的Debian系列shell命令工具

### **命令地图**：
<pre><code>
 help
  ├─ 获取类
  │  ├── get_git   		生成git同步指令，参数1：项目名
  │  ├── get_number		随机生成一串长度为20的数字
  │  ├── get_uname  		随机生成用户名 长度为6
  │  ├── get_passwd		随机生成一串长度为20的高强度密码
  │  └──..help			获取帮助信息
  │
  ├─ 打开类
  │  ├── open-hosts		打开hosts文件
  │  ├── open-wifi   		打开wifi
  │  ├── open-path		打开path文件
  │  └── update-path		获取更新path文件命令
  │
  ├─ 修改类
  │ └── change-mac		生成修改mac命令
  │
  └─ Hacker类
       └── java rand_shenfen 随机生成身份信息

tools_other
  └─ baota
       └──install.sh		宝塔面板一键安装程序

folders	（自用）
  ├─ open-angular.sh		打开angular项目
  ├─ open-bike.sh		打开bike项目
  └─ open-web.sh		打开web项目

系统常用命令手册
   ├──安装pip和pip3		sudo apt install -y python-pip python3-pip
   ├──系统升级命令		sudo apt-get update && sudo apt-get dist-upgrade -y
   ├──mongodb数据库备份		mongodump --host 127.0.0.1 --port 27017 -d leanote -o folder
   └──mongodb数据库恢复		mongorestore -h 127.0.0.1:27017 -d leanote folder
   └──mongodb数据库添加用户	<a href="https://github.com/leanote/leanote/wiki/QA#%E5%A6%82%E4%BD%95%E7%BB%91%E5%AE%9A%E5%9F%9F%E5%90%8D">https://github.com/leanote/leanote/wiki/QA#%E......</a>

</code></pre>