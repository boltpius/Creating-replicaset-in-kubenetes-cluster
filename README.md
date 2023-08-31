# Creating-replicaset-in-kubenetes-cluster
Replicaset is used to ensure that the specified number of pods are always in a running state in this task, it is set to "4". Another reason for using it is to scale and share load across multiple pods on different nodes created in the cluster.
The ReplicaSet was configured with the following details:

- Name: The ReplicaSet was named "httpd-replicaset".
- Image: The httpd image with the latest tag, "httpd:latest", was used to run the desired workload.
- Labels: The ReplicaSet had labels defined to identify it as an httpd app with the label "app: httpd" and the label "type: front-end".
- Container Name: The container within the ReplicaSet was named "httpd-container".
- Replicas: The ReplicaSet was set to maintain a desired number of replicas, which was specified as 4 in this case.

<img width="1423" alt="Screenshot 2023-08-31 at 09 03 38" src="https://github.com/boltpius/Creating-replicaset-in-kubenetes-cluster/assets/127052041/746d47fd-dd8d-48a4-bd5b-dfbd99705874">
<img width="1509" alt="Screenshot 2023-08-31 at 09 04 18" src="https://github.com/boltpius/Creating-replicaset-in-kubenetes-cluster/assets/127052041/c7a10163-d295-4fb7-a120-ad31dcd7ba8d">
<img width="1509" alt="Screenshot 2023-08-31 at 09 04 28" src="https://github.com/boltpius/Creating-replicaset-in-kubenetes-cluster/assets/127052041/d2b66226-2a79-4a6f-880a-7eeab48f9c12">
