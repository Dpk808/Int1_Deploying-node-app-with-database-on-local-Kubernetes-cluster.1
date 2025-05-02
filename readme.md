**Deploying a Node App on Kubernetes:**

Application from my dockerhub


(Deployed Application with Database into local Kubernetes Cluster )





1.Starting Minikube:


![image alt](https://github.com/Dpk808/Int1_Deploying-node-app-with-database-on-local-Kubernetes-cluster.1/blob/main/Screenshots/1.%20started%20minikube.png)


2.Applying the yaml files:

<pre> ``` mongo-config.yaml -- one configurations for all pods mongo-secret.yaml -- stores credentials mongo.yaml -- database webapp.yaml -- app ``` </pre>

Command:
kubectl apply -f .

Applying all yaml files


![image alt](https://github.com/Dpk808/Int1_Deploying-node-app-with-database-on-local-Kubernetes-cluster.1/blob/main/Screenshots/2.%20Apply%20the%20yaml.png)





3.Checking the status of the deployments

![image alt](https://github.com/Dpk808/Int1_Deploying-node-app-with-database-on-local-Kubernetes-cluster.1/blob/main/Screenshots/3.%20Current%20status.png)



4.Finding minikube IP for external access:

![image alt](https://github.com/Dpk808/Int1_Deploying-node-app-with-database-on-local-Kubernetes-cluster.1/blob/main/Screenshots/4.%20Finding%20minikube%20IP%20for%20external%20access.png)

5.Port forwarding the deployment:


![image alt](https://github.com/Dpk808/Int1_Deploying-node-app-with-database-on-local-Kubernetes-cluster.1/blob/main/Screenshots/5.%20Port%20forwarding%20as%20minikube%20does%20not%20start.png)

6.Verifying the app on browser:

![image alt](https://github.com/Dpk808/Int1_Deploying-node-app-with-database-on-local-Kubernetes-cluster.1/blob/main/Screenshots/6.%20Node%20App%20Running.png)
