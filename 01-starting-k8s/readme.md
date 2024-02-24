# Command run:
# sudo chown -R $USER:$USER /home/haison
# sudo chown -R $USER:$USER /home/haison/.minikube
# sudo systemctl enable kubelet.service
# ls -ld /home/haison /home/haison/.minikube
# 0. sudo sysctl fs.protected_regular=0 => run this command if have error
# 1. sudo minikube start --driver=docker --force 

######
# kubectl apply -f test-k8s.yml
# kubectl get pods/services/deployments
# delete => kubectl delete deployment "deployment-name" <====> kubectl delete -f=service-k8s.yml











