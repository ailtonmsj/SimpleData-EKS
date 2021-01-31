# SimpleData-EKS

Create a cluster with 2 EC2 t2.micro with 10GB volume each one.

The application is a simple application that return the current time, the application is behind a ALB that expose the port 8080.

### To create a cluster EKS

$ eksctl create -f eks-create-cluster-simpledata.yaml

### To deploy the pods:

$ kubectl apply -f simpledata-deploy-eks.yaml

