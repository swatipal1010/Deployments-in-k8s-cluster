## nginx server deployment on k8s cluster inside my namespace
- Corresponding yaml code for the deployment
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/612ed44d-9dad-43ae-8bf8-2a21992044e3)

- Cammands to be executed to connect to the cluster, setting my namespace as the default namespace inside the cluster and listing the pods running inside my namespace in the cluster.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/be681f26-0239-4ded-aace-e5c44dcd6c09)

- Status of pods of nginx-server created in the namespace of the cluster.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/b177575f-1021-488e-b663-06efe2050ee4)

- Command to run the deployment
  - use port forwarding to interact with the pods from our local machine.
  - copy the local address received by executing the below command and cpy & paste the address on the web-browser for deployment to run succressfully locally.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/34991d84-ba59-4bb1-88a6-90d1e7e610c4)

- Result in the browser
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/7448de9a-4aa4-4a02-a30b-3a4c5b878596)

