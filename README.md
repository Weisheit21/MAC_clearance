# MAC_clearance
MAC_clearance_application
steps!
aim1: App来源修改
terminal: sudo spctl --master-disable
terminal: password
ensure: 系统偏好设置_安全与隐私_通用_允许从以下位置下载的App_任何来源
aim2: 权限开启fix_do not have permission to open the application 'xxx'
app右键：显示包内容_contents_MacOS_xxx
terminal: (sudo) chmod +x xxx(将xxx拖入terminal)
terminal: password
back_app: 破解成功！
