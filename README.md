# Complex-Project
this project include java,javascript,java web,html5+css3,jsp and so on.
## 一、JS插件
1. JS日历插件包含中国农历以及二十四节气
  - [x] 公历日期及节日
  - [x] 农历日期及节日
  - [ ] 农历二十四节气
## 二.Java技术
1. 共享工具
- 日期格式化
- http请求[http请求支持认证机制(用户名密码校验)]
2. 支持Canal服务(MySQL的binlog监控)
3. 支持Cassandra连接及其接口服务封装
4. 支持传统数据库JDBC或Druid方式接口封装
5. 支持数据仓库JDBC或Druid方式接口封装
7. 支持Elasticsearch的Http API或Java API底层封装
8. Maven配置以及丰富Maven仓库(setting.xml|pom.xml)
9. 支持Kafka消息队列服务
10. 支持MongoDB连接及其接口服务封装
## 三.Linux命令
1. 创建目录
```bash
sudo mkdir /home/test
```
2. 文件夹赋予读写执行权限
```bash
chown -R user /home/elk //读写权
chmod +x /home/elk //可执行权限
```
3. 解压文件
```bash
sudo tar -zxvf /home/user/jdk-8u144-linux-x64.tar.gz -C /home
```
4. 跨服务器拷贝
```bash
scp -r /home/elk root@192.168.1.2:/home
```
根据提示输入密码

5. tracert追踪
```bash
tracert -d www.google.com
```
6. vim保存无权限处理
```bash
w !sudo tee %
```
7.Windows修复
```cmd
dism/Online /Cleanup-Image /CheckHealth
dism/Online /Cleanup-Image /RestoreHealth
sfc /scannow
```
8.Windows重置网络
```
netsh winsock reset
```
9.Windows添加硬件
```
HDWWIZ
```
10.windows由于没有远程桌面授权服务器可以提供许可证，远程会话被中断。请跟服务器管理员联系

```
运行》regedit
删除目录：
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server\RCM\GracePeriod
#若无法删除，右键-》属性，权限--》完全控制后，再删除
重启电脑

```
11.Windows设置桌面图标
```
rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0
```
12.Linux给目录rw无d权限
```
#允许soft目录添加读写权限不允许删除(+/-a 让文件或目录仅供附加用途)
chattr -R +a soft
#撤销权限
chattr -R -a soft
```
## 四. NodeJS配置
1. grunt安装
```bash
npm install -g grunt-cli
```
