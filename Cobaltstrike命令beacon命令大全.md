## Cobaltstrike命令/beacon命令大全

```shell
browserpivot 注入受害者浏览器进程
bypassuac 绕过UAC
cancel 取消正在进行的下载
cd 切换目录
checkin 强制让被控端回连一次
clear 清除beacon内部的任务队列
connect Connect to a Beacon peerover TCP
covertvpn 部署Covert VPN客户端
cp 复制文件
dcsync 从DC中提取密码哈希
desktop 远程VNC
dllinject 反射DLL注入进程
dllload 使用LoadLibrary将DLL加载到进程中
download 下载文件
downloads 列出正在进行的文件下载
drives 列出目标盘符
elevate 尝试提权
execute 在目标上执行程序(无输出)
execute-assembly 在目标上内存中执行本地.NET程序
exit 退出beacon
getprivs Enable system privileges oncurrent token
getsystem 尝试获取SYSTEM权限
getuid 获取用户ID
hashdump 转储密码哈希值
help 帮助
inject 在特定进程中生成会话
jobkill 杀死一个后台任务
jobs 列出后台任务
kerberos_ccache_use 从ccache文件中导入票据应用于此会话
kerberos_ticket_purge 清除当前会话的票据
kerberos_ticket_use 从ticket文件中导入票据应用于此会话
keylogger 键盘记录
kill 结束进程
link Connect to a Beacon peerover a named pipe
logonpasswords 使用mimikatz转储凭据和哈希值
ls 列出文件
make_token 创建令牌以传递凭据
mimikatz 运行mimikatz
mkdir 创建一个目录
mode dns 使用DNS A作为通信通道(仅限DNS beacon)
mode dns-txt 使用DNS TXT作为通信通道(仅限D beacon)
mode dns6 使用DNS AAAA作为通信通道(仅限DNS beacon)
mode http 使用HTTP作为通信通道
mv 移动文件
net net命令
note 备注
portscan 进行端口扫描
powerpick 通过Unmanaged PowerShell执行命令
powershell 通过powershell.exe执行命令
powershell-import 导入powershell脚本
ppid Set parent PID forspawned post-ex jobs
ps 显示进程列表
psexec Use a service to spawn asession on a host
psexec_psh Use PowerShell to spawn asession on a host
psinject 在特定进程中执行PowerShell命令
pth 使用Mimikatz进行传递哈希
pwd 当前目录位置
reg Query the registry
rev2self 恢复原始令牌
rm 删除文件或文件夹
rportfwd 端口转发
run 在目标上执行程序(返回输出)
runas 以另一个用户权限执行程序
runasadmin 在高权限下执行程序
runu Execute a program underanother PID
screenshot 屏幕截图
setenv 设置环境变量
shell cmd执行命令
shinject 将shellcode注入进程
shspawn 生成进程并将shellcode注入其中
sleep 设置睡眠延迟时间
socks 启动SOCKS4代理
socks stop 停止SOCKS4
spawn Spawn a session
spawnas Spawn a session as anotheruser
spawnto Set executable tospawn processes into
spawnu Spawn a session underanother PID
ssh 使用ssh连接远程主机
ssh-key 使用密钥连接远程主机
steal_token 从进程中窃取令牌
timestomp 将一个文件时间戳应用到另一个文件
unlink Disconnect from parentBeacon
upload 上传文件
wdigest 使用mimikatz转储明文凭据
winrm 使用WinRM在主机上生成会话
wmi 使用WMI在主机上生成会话
argue 进程参数欺骗
```



