## We want to communicate to the deployed nginx server from deployed 2048 game.
- First we need to get the terminal access of the 2048 game pod using "kubectl exec -it game2048-deployment-5c74884847-pwcrk -- sh" command where 'game2048-deployment-5c74884847-pwcrk' is the name of the 2048 game pod.
- Then we need to use "curl mynginx.swati-ns.svc.cluster.local:8080" command to successfully communicate with the 2048 game deployment. Here 'mynginx' is the name of the service we want to communicate with and '8080' is the service port it listens on.

- ![image](https://github.com/swatipal1010/Deployments-in-k8s-cluster/assets/110754474/348d1e0d-ef09-4ea4-9270-3faa3e5108b0)

- **NOTE :** If you dont have curl in the terminal of the container use the following commands inside the terminal of the container:-
  - apk update
  - apk add curl
  
  
