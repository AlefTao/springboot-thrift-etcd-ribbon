# springboot-thrift-etcd-ribbon
基于springboot和thrift的简单rpc功能，目标就是简单、轻量

一般比如dubbo使用的zk做服务注册和发现，但是既然为了轻量级目标，就把zk替换成了etcd

路由算法目前选用了ribbon包的开源默认实现
