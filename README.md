## 黑马点评

> springboot,mysql,redis

springboot单体项目，主要学习使用redis的各种场景，各种数据结构

找不到主类的解决办法
springboot项目有时直接点运行会提示找不到主类，造成这种现象的原因是因为项目中maven自动编译生成的target文件夹出了问题，例如vscode没有自动编译，或者开发者删除了target文件夹中的内容导致直接运行就出现了这个错误。
解决的办法就是手动运行maven命令的clean和compile重新编译，这样再次点击运行就可以启动了。
```sh
mvn clean
mvn compile
```
