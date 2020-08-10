# certified-kubernetes-administrator-course
Certified Kubernetes Administrator - CKA Course

Note: This is currently work in progress. Please check back again soon.

Installation

vagrant up
kubeadm init --pod-network-cidr 10.244.0.0/16 --apiserver-advertise-address=192.168.56.2
kubectl apply -f "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 | tr -d '\n')"
