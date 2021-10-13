kubectl describe pod nginx-pod  
kubectl get pods --watch  
kubectl run nginx-pod --image=nginx  
kubectl apply -f .\primeiro-pod.yml  
kubectl delete pod nginx-pod  
kubectl delete -f .\primeiro-pod.yml  
kubectl rollout history deployment nginx-deployment  
kubectl get rs  
kubectl get deployments
kubectl get deploy
kubectl annotate deployment portal-noticias-deployment kubernetes.io/change-cause="Criando portal de notícias na versão 1"
kubectl rollout undo deployment <nome do deployment> --to-revision=<versão a ser retornada>