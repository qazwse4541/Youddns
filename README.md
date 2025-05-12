# Youddns【只能对接cloudflare的域名，区域id，域名，全局token，邮箱】
Youddns二级域名分发网站源码
域名/install【网站安装路径，管理员账号：admin,密码：12345678【123456】】


ssl使用相关：
使用命令
chmod +x apply_cert.sh
./apply_cert.sh box.cnboxs.dpdns.org


接口调用：https://xxx.com/get_info.php?subdomain=box.cnboxs.dpdns.org

ddns[动态公网解析]使用说明：
GET https://dns.cngames.site/ddnsapi.php?domain=你的域名&token=你的API Token&addr=你的IPv4或IPv6公网地址
参数：
• domain=你的域名
• token=API Token
• addr=IP地址
返回：
• 成功时返回 JSON 格式：`{"success": true, "message": "DNS 解析更新成功"}`
• 失败时返回 JSON 格式：`{"success": false, "message": "错误信息"}`
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
演示站：https://dns.cngames.site/【大家可以联系QQ：2014131458获取演示网站激活码，每个人免费一个激活码。】
前台：
![image](https://github.com/user-attachments/assets/3e2fb6bc-c156-45a4-b7c1-60aee49057fb)
![image](https://github.com/user-attachments/assets/589f30a3-41a6-435e-aa69-44822a180e52)
![image](https://github.com/user-attachments/assets/462825b7-3874-4331-84d8-dd337ffb3a94)
![image](https://github.com/user-attachments/assets/dc93e29c-c462-4466-9220-42674f83f361)
![image](https://github.com/user-attachments/assets/3e7ed9c0-f13a-40d7-9e30-647fc2677bbf)

后台：
![image](https://github.com/user-attachments/assets/c4065d4b-dd88-4415-94ae-e784d620e047)
ssl:
![image](https://github.com/user-attachments/assets/b0da9e23-023c-46c9-89d9-926eec724f11)

