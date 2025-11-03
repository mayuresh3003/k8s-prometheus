# Steps to bring up kafka-cluster in kind cluster

1. Apply kafka-namespace.yaml to create namespace 
2. Execute the following command to bring up strimzi-operator deployment kubectl apply -f https://strimzi.io/install/latest?namespace=kafka -n kafka
3. Apply strimzi-cluster-operator-rbac.yaml
4. Apply strimzi-nodes-access.yaml
5. Apply kafka-deployment.yaml
6. Apply kafka-nodepools.yaml
