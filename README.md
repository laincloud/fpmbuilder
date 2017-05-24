# fpmbuilder

方便的打包 rpm 的工具，可以不用写复杂的 sepcs。

fpm 工具文档地址 https://fpm.readthedocs.io/en/latest/

## 本项目使用方式

所有构建均在 Docker 环境中进行，因此不用担心污染本地环境。

步骤如下：

1. 启动一个容器 `docker run -it laincloud/fpmbuilder:latest bash`
2. 执行你的 fpm 构建脚本吧！
