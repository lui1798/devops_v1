项目名称：项目自动化运维平台
关于 opsdev_java:本来是想是用 devops_java 命名，意思就是 开发运维的java系统，考虑名称太专业，
容易误导搜索引擎，就把名字前面调了个顺序。

项目是用多个模块组成，
opsdev-commons : 通用模块，只负责一些通用类的创建，没有运行逻辑
opsdev-core:远程管理通道，负责对cmdb 中的服务器进行远程操作，执行远程命令，分发文件等工作
opsdev-center:中心管理平台，运维人员通过该平台操作项目的打包，
                并通过远程部署到基础设施上面，通过一些列标定制的任务，实现对项目的自动化远程部署


