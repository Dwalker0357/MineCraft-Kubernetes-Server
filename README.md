# MineCraft-Kubernetes-Server

<h1>Vanilla V1:</h1>
<br>
<h2>Server Specs:</h2>
<br>
Ram: 10gb
<br>
Vcpu: 4
<br>
Volume: 2GB
<br>
Replicas: 1
<br>
<br>
<h2>GCP cluster Specs:</h2>
<br>
gcloud container clusters create ravensword --num-nodes=3 --machine-type=e2-standard-4 --zone=us-central1-a
<br>
<br>
e2-standard-4 (4 vCPUs, 16 GB memory)
<br>
e2-standard-4 (4 vCPUs, 16 GB memory)
<br>
e2-standard-4 (4 vCPUs, 16 GB memory)

<br>
<br>
<h1>Google Cloud Platform Cluster</h1>

![cluster](https://user-images.githubusercontent.com/77269929/111881105-f9980c80-89a6-11eb-89e1-dd464000c187.png)

![nodes](https://user-images.githubusercontent.com/77269929/111881109-fa30a300-89a6-11eb-8842-41e07fd4329e.png)

<br>
<h1>Yaml File Deployment</h1>

![deployment](https://user-images.githubusercontent.com/77269929/111881110-fa30a300-89a6-11eb-9459-499ee4575789.png)

<br>
<h2> Server Deployment Pod Created And Running:</h2>

![pod](https://user-images.githubusercontent.com/77269929/111881112-fac93980-89a6-11eb-8e67-082f90e32ba3.png)

<br>
<h2> Server Deployment Replicas 1/1 Successfully Created:</h2> 

![deploymentcli](https://user-images.githubusercontent.com/77269929/111881113-fac93980-89a6-11eb-84f3-ad1b98eab456.png)

<br>
<h2> LoadBalancer Service Successfully Created: </h2>

![LoadBalancer](https://user-images.githubusercontent.com/77269929/111881107-f9980c80-89a6-11eb-8e8d-40a31febbea8.png)

<br>
<h2> Deployed Server Player Logs:</h2>

![logs](https://user-images.githubusercontent.com/77269929/111881111-fac93980-89a6-11eb-9775-a94857b11de7.png)

<br>
<h2> Connecting To Server Via LoadBalancer IP Address

![serverinfo](https://user-images.githubusercontent.com/77269929/111881101-f8ff7600-89a6-11eb-8f7e-c96031843eed.png)

<br>
<h2>Successful Ping To Deployed Server</h2> 

![home](https://user-images.githubusercontent.com/77269929/111881108-fa30a300-89a6-11eb-8b3b-bef22ce72b17.png)

<br>

<h2> Successful Game Connection Via LoadBalancer Port 25565 </h2>

![game](https://user-images.githubusercontent.com/77269929/111881114-fb61d000-89a6-11eb-9cc7-73cb24a0c686.png)

