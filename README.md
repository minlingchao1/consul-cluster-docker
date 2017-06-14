# consul-cluster-docker
在rancher上构建的consul集群

# 启动后，其他docker服务内只需要添加外链,即可在配置中使用consul
```
external_links: 
    - datamgt-cloud-base/consul-register:consul
```
