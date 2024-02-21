# Solution

kubectl get namespaces

kubectl create namespace dev
kubectl get namespaces

kubectl get namespaces > /home/cloud_user/namespaces.txt
cat /home/cloud_user/namespaces.txt

kubectl get pods --all-namespaces | grep quark > /home/cloud_user/quark-namespace.txt
cat /home/cloud_user/quark-namespace.txt