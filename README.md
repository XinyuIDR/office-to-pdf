# 使用说明

### 原代码仓在[这里](https://github.com/idrsolutions/office-to-pdf-conversion)

在开始之前，你必须使用以下命令打包构建：
```
mvn clean package
```

接下来，你需要安装 [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) 和 [Azure Functions Core Tools](https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Clinux%2Ccsharp%2Cportal%2Cbash)。

要在本地测试项目，可以运行：
```
mvn azure-functions:run
```

要将项目上传到 Azure，可以运行：
```
mvn azure-functions:deploy
```
