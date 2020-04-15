来源：https://developer.android.com/guide/topics/security/permissions?hl=zh-cn#defining

内容：

注：系统不允许多个软件包使用同一名称声明权限，除非所有软件包都使用同一证书签署。如果软件包声明权限，则系统不允许用户安装具有相同权限名称的其他软件包，除非这些软件包使用与第一个软件包相同的证书签署。为避免命名冲突，建议对自定义权限使用相反域名样式命名，例如 com.example.myapp.ENGAGE_HYPERSPACE。
