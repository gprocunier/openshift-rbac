

oc describe rolebinding.rbac -n projectx89

oc describe role cicd-role

 oc adm node-logs --role=master --path=kube-apiserver/ --as system:admin
 