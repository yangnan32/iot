# IoT Edge {#concept_pds_jsq_3fb .concept}

本章将为您介绍如何配置IoT Edge的各个配置项。

|配置项|描述|
|---|--|
|服务名|可被其他服务模块调用的服务名称，租户下的边缘集群内服务名唯一|
|日志存储区大小|为当前节点分配用于存储日志数据的磁盘资源数，单位Gi|
|cpu配额|为当前节点分配CPU资源数，单位m，m表示千分之一的CPU资源|
|memory配额|为当前节点分配内存资源数，单位为Mi或Gi，Mi=1024\*1024，Gi=1024\*Mi|
|运行时数据区大小|为当前节点分配用于存储服务运行时所需要的磁盘资源数，单位Gi|
|cpu限制|当前节点CPU资源数最大分配额度，单位m，m表示千分之一的CPU资源|
|memory限制|当前节点内存资源数最大分配额度，单位为Mi或Gi，Mi=1024\*1024，Gi=1024\*Mi|
|服务类型|声明对外提供服务的类型，目前只支持NodePort形式（集群节点IP地址+节点端口，可通过运维页面**外部端口**获取）|

