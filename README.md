## 使用文档
- 修改 alertmanager.yaml中的邮件或者钉钉调用
- 修改 mail-template.tmpl 中     <strong>浙江智慧党建-Labels</strong><br />  为自己环境标识符
- 修改 deploy中etcd ssl证书位置
- sh deploy  部署prometheus监控pod 
- kubectl -n monitoring get po  查看pod状态
- kubctl -n monitoring  get svc  查看暴露的服务端口