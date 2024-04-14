# Zabbix com Docker Compose
我们在Github中提供的docker-compose.yml文件的配置方式是，Docker创建4个容器：zabbix-服务器、zabbix-前端、graph ana和MySQL。
Zabbix、Graphana和MySQL的官方图像已经被使用。
咨询的链接在本文的末尾。
当运行docker-compose up命令时，docker将自动向上移动Zabbix、Graphana和MySQL容器。
此外，Zabbix已经连接到MySQL数据库，Grafana已经安装了Zabbix插件。
在找到docker-compose.yml文件的目录上运行以下命令，以淹没容器：

docker-compose up -d


zabbix账号：Admin 
zabbix密码：zabbix
