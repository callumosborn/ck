# Solution

kubectl get pv
kubectl get pv --sort-by=.spec.capacity.storage > pv_list.txt

kubectl exec quark --container=busybox --namespace=beebox-mobile -- cat /etc/key/key.txt > key.txt

kubectl apply -f deployment.yml

kubectl delete svc/beebox-auth-svc --namespace=beebox-mobile