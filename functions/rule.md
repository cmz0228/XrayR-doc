# 审计功能说明

1. 请在前端审计规则处填写任意正则表达式，如 `baidu.com`将屏蔽所有baidu的域名。暂不支持bt协议的审计。

## 本地审计规则设置

针对不支持远程设置审计规则的面板：如V2board，可以在本地配置文件`
RuleListPath`设置本地规则文件路径。规则文件不需要定义文件类型，每条正则规则一行，默认本地规则ID标号为-1。

配置文件详见：[配置文件说明](../config/README.md)

**本地规则文件示例**
```
baidu.com
google.com
```