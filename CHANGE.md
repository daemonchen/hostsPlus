hostsPlus 变更日志
====================

## ver 1.0.1 (2014-7-28)

添加：

1. 权限问题导致hosts写入失败时，引导至帮助页面

## ver 1.0.0 (2014-7-24)

添加：

1. 添加自动探测活动网卡名字功能，能自适应兼容Windows和Mac系统
2. 添加方案保存菜单
3. 添加字体大小修改功能

## ver 0.9.7 (2013-5-29)

添加：

1. 系统栏图标添加方案选择菜单

修正：

1. 更新codemirror到最新3.12版，修正了某些特殊场景下部分区域隐藏的问题

调整：

1. 当无分组信息时，系统栏图标右键菜单中不显示分组菜单

## ver 0.9.6 (2013-4-24)

添加：

1. 添加由于hosts权限问题而写入失败的提醒
2. 添加导入HAR文件批量CDN检测功能

修正：

1. 修正检测远程Hosts导致的内存泄露问题

## ver 0.9.5 (2013-3-12)

添加：

1. 添加搜索和替换功能，并支持正则搜索
2. 添加全局备份和恢复功能，方便重装系统时备份数据
3. 添加远程Hosts功能，以支持公司内全局范围的Hosts共享
4. 添加CDN一致性检测功能，发布时可轻松检测全球生效情况
5. 添加由于hosts权限问题而写入失败的提醒
6. Mac版本添加DNS切换支持

调整：

1. codeMirror升级为v3.1

## ver 0.9.4 (2012-9-1)

添加：

1. 切换方案和分组时，会提示“您的编辑结果还没保存，需要为您保存吗？”，若选择“是”会自动保存

修正：

1. 按Ctrl + P等特殊按钮会插入一些看不见的特殊字符
2. 在启用重定向到主机名功能时，修正了内存泄露问题
3. 修改后再撤销，标题栏没有恢复为未修改状态
4. IE DNS缓存关闭后重启软件没有记住状态问题的修正
5. 当同一个机器名或域名被多次重定向时，会发起多次请求的修正
6. hostsPlus被外部强制关闭会造成数据丢失的问题

调整：

1. 由GPL协议调整为更开放的MIT协议
2. codeMirror升级到2.32版本
3. 标题里的方案名调整显示到最前面
4. 取消Ctrl + G的限制，可在任意行新建分组


## ver 0.9.3 (2012-8-7)

添加：

1. 添加Linux和Mac两个平台的支持