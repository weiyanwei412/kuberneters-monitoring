## 使用文档
- 修改 alertmanager.yaml中的邮件或者钉钉调用
- 修改 alertmanager.yaml  headers: { Subject: " 测试环境 k8s warning" }  区分环境标识符
- 修改 deploy中etcd ssl证书位置
- 修改 manifests/prometheus/kube-controller-manager-kube-scheduler-Endpoints.yaml master 节点IP列表
- sh deploy  部署prometheus监控pod 
- kubectl -n monitoring get po  查看pod状态
- kubctl -n monitoring  get svc  查看暴露的服务端口
