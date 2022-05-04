# Bypass-script

### 免责声明

该工具仅用于安全研究，禁止使用工具发起非法攻击等违法行为，造成的后果使用者负责

### 介绍

`Cobaltstrike`免杀插件

调用https://github.com/Sec-Fork/GoBypass免杀生成工具

### 准备工作

下载`GoBypass`免杀工具到cs客户端的启动目录。

下载地址：https://github.com/sssqp/GoBypass（因为原版不支持mac和Linux下生成exe，

所以建议下载我fork后的修改版本）

###### 注意事项：

1. 确保安装`Golang`且环境变量中包含`go`否则无法编译
2. 请在`GoBypass`目录先执行`go env -w GO111MODULE=on`然后`go mod download`命令下载依赖
3. 如果下载依赖过慢配置镜像`go env -w GOPROXY=https://mirrors.aliyun.com/goproxy`

### 示例

![image-20220504103235568](https://sssq0p-1253744829.cos.ap-nanjing.myqcloud.com/img/image-20220504103235568.png)

![image-20220504103413204](https://sssq0p-1253744829.cos.ap-nanjing.myqcloud.com/img/image-20220504103413204.png)
