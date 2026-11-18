
List noduri cluster = kubectl get nodes -o wide

List pod-uri dintr-un name space = kubectl get pods -n kube-system -o wide

Listeaza DaemonSet-urile = kubectl get daemonsets -n kube-system

Containere care ruleaza acum = docker ps
Toate containerele, chiar si cele oprite = docker ps -a

Imaginile descarcate (AMI-uri) = docker images


Creaza cluster = kind create cluster --name cnis-lab --config kind cnis.yaml
Sterge cluster = kind delete cluster -- name cnis-lab
