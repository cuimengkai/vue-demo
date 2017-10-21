项目介绍:
1.为什么要创建assets这个文件夹,因为在服务器上该文件夹下面的文件默认是不会被编译的
2.index.html是创建一个字典 用于快速定位知识点
3.全局添加一个用于开发的临时服务器live-server(前提要安装node) 项目根目录下执行 live-server 启动服务
4.项目根目录下执行 npm init 创建package.json 项目依赖描述文件

知识点:1.v-if&v-else 和 v-show的区别是啥?
v-if： 判断是否加载，可以减轻服务器的压力，在需要时加载。
v-show：调整css dispaly属性，可以使客户端操作更加流畅。
5.项目启动
live-server