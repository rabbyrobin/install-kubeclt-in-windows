# install-kubeclt-in-windows

https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/#install-kubectl-binary-on-windows-via-direct-download-or-curl

#connect the node with eks cluster

aws sts get-caller-identity  

aws eks --region ap-south-1 update-kubeconfig --name eks-first-cluster
