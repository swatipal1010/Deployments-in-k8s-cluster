## nginx server deployment on k8s cluster inside my namespace
- Corresponding yaml code for the deployment
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/612ed44d-9dad-43ae-8bf8-2a21992044e3)

- Cammands to be executed to connect to the cluster, setting my namespace as the default namespace inside the cluster and listing the pods running inside my namespace in the cluster.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/be681f26-0239-4ded-aace-e5c44dcd6c09)

- In the above command "kubectl get pods", all the pods available within the namespace of the k7s gets displayed. But we can use "kubectl get pods -l app=nginx" command to list the pods running in the nginx deployment only.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/3572fa9c-f3f0-4d5b-af68-5830c8b3d466)

- To display the information about the deployment, we can use "kubectl describe deployment nginx-deployment" command on the terminal.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/8b330b3a-3f7c-4ce9-b366-5526661c0dab)

- Status of pods of nginx-server created in the namespace of the cluster.
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/b177575f-1021-488e-b663-06efe2050ee4)

- Command to run the deployment
  - use port forwarding to interact with the pods from our local machine.
  - copy the local address received by executing the below command and cpy & paste the address on the web-browser for deployment to run succressfully locally.
    
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/34991d84-ba59-4bb1-88a6-90d1e7e610c4)

- Result in the browser
![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/7448de9a-4aa4-4a02-a30b-3a4c5b878596)

