### 获取Root权限，可改root密码的一键脚本

VPS应用环境：纯IPV4、纯IPV6、双栈IPV4+IPV6，

支持root或非root模式下运行。

脚本集成获取最高权限属性（以防止被暴力破解后改属性造成无法修改root密码）

后续再次执行脚本意味着更改root密码！！

-----------------------------------------------------------------------------------------

一键脚本：

```
bash <(curl -sSL https://raw.githubusercontent.com/panhuanghe/vpsroot/main/root.sh)
```

My own:
```
bash <(curl -sSL https://raw.githubusercontent.com/AndersonGhost/one-clik-root/main/root.sh)
```
用户名：root，密码必须自定义。

登录SSH时，请更改原用户名为root，并输入自定义密码！

--------------------------------------------------------------------------------------

提示：密码不要设置得过于简单，容易被破解。如有密钥文件要保存好，以防万一！



