On this project I used Docker and Kubernetes to deploy a fleet management system. The system track each vehicle position in the map and where it's going.

First I started with minikube, locally. After I tested, it was migrated to AWS.

The system architeture:
![alt](Architeture.png)

Running system using AWS
![alt](sample.png)

To visualize the log and traffic flow I also implement Kibana and Grafana for a monitorig solution.
![alt](Grafana1.png)

Cluster Monitoring - Utilization, Saturantion and Errors (USE Method)
![alt](Grafana2.png)

Cluster Monitoring - Utilization, Saturantion and Errors (USE Method). CPU Saturation in a node.
![alt](Grafana3.png)


