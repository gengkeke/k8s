```shell
#生成资源清单
 kubectl create deploy nginx --image=nginx -o yaml --dry-run >1.yaml
 #导出资源清单
 kubectl get deploy nginx -o yaml --export >2.yaml
 
```