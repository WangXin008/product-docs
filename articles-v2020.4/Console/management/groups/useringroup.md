# 管理资源组用户

## 查看资源组(或租户)下用户
在“全局管理”-“资源组管理”页面中，点击任意“资源组名称”即可进入查看该资源组下已经被添加的用户列表。
![groups](https://docimages.blob.core.chinacloudapi.cn/images/Console/group/点击资源组名称.png)
在用户列表中可以看到每个用户在当前资源组下的对应角色，也可以点击其他的资源组名称（或租户名称），查看在当前资源组（或租户）下的用户及其对应角色。
（控制台引入RBAC管理模式，即资源组-用户-角色-权限的管理模式，用户可以配置在不同资源组，在不同资源组下享有不同角色。）
![groups](https://docimages.blob.core.chinacloudapi.cn/images/Console/group/查看资源组内的用户.png)

注意：若将用户直接添加到租户下并赋予角色，意味着该用户在任意资源组下均具有该角色。例如将用户A添加到租户层级下并赋予角色A（角色A仅拥有查看机器人权限），则用户A在任意资源组下均具有查看机器人权限。

## 添加用户到资源组（或租户）
**1）添加用户到资源组**
选定资源组后，点击**添加**打开添加用户弹窗。以在下拉框内输入需要查找的用户和角色进行模糊查询，请选择你想要添加的用户和用户对应的角色。点击“**保存**”即可完成添加。
**2）添加用户到租户**
选定租户后（仅有一个租户），点击**添加**打开添加用户弹窗即可进行添加。
![groups](https://docimages.blob.core.chinacloudapi.cn/images/Console/group/资源组内的添加用户.png)
注意：若将用户直接添加到租户下并赋予角色，意味着该用户在任意资源组下均具有该角色。例如将用户A添加到租户层级下并赋予角色A（角色A仅拥有查看机器人权限），则用户A在任意资源组下均具有查看机器人权限。
