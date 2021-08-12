# appVoteKubernetes
kubectl get all -n vote
kubectl create -f  services/ --save-config --record
kubectl create -f deployments/ --save-config --record
kubectl create -f namespaces/vote.yaml --save-config --recor

