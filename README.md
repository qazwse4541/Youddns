# Youddns
Youddns二级域名分发网站源码
域名/install【网站安装路径，管理员账号：admin,密码：12345678【123456】】


ssl使用相关
使用命令
chmod +x apply_cert.sh
./apply_cert.sh box.cnboxs.dpdns.org


接口调用：https://xxx.com/get_info.php?subdomain=box.cnboxs.dpdns.org


注意（安装jq）
Ubuntu / Debian
sudo apt update
sudo apt install jq -y
CentOS / RHEL / AlmaLinux / Rocky Linux
sudo yum install jq -y
或者如果你使用的是 dnf或者Fedora
sudo dnf install jq -y
macOS（使用 Homebrew）：
brew install jq
Alpine Linux
apk add jq
注意（shell_exec()记得从php禁用函数里面删掉）

youddns官方QQ群：819229551【有接手二开源码的私信我哦】
