基于spring给ibatis提供sharding支持，类似hibernate的hibernate-shards，支持数据库的水平划分(horizontal partition)

目前处于初期开发阶段，功能还比较简单

  1. 从http://code.google.com/p/ibatis-sharding/source 取得源代码，你可能需要[svn](http://subversion.tigris.org)客户端
  1. 编译代码，你需要使用[maven2](http://maven.apache.org)，下载并安装
  1. 当然，你还需要[java](http://java.sun.com)，下载并安装
  1. 在源代码的目录里，执行 mvn 即可，系统会执行单元测试，并打包出ibatis-sharding-{version}.jar到target目录下，另外，第一次编译时，maven可能需要下载需要的软件包

如果有兴趣一起设计和开发，请联系我。


---


for who impatient:
  1. install jdk and maven(at least 2.0.x )
  1. svn co http://code.google.com/p/ibatis-sharding/source ibatis-sharding
  1. cd ibatis-sharding ; mvn
  1. it will run a simple example in the dist