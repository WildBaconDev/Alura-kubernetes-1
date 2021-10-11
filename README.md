kubectl describe pod nginx-pod
kubectl get pods --watch
kubectl run nginx-pod --image=nginx
kubectl apply -f .\primeiro-pod.yml
kubectl delete pod nginx-pod
kubectl delete -f .\primeiro-pod.yml