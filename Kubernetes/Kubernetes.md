## Minikube-Setup
- https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/
- Install kubectl binary with curl on Linux
<img width="866" height="83" alt="image" src="https://github.com/user-attachments/assets/6b17c23d-c4d4-4fff-95c2-387b11d47419" />

___
- Created test pod - kubectl run test --image=nginx --restart=Never
- kubectl get pod -A
<img width="806" height="170" alt="image" src="https://github.com/user-attachments/assets/57ac3b87-a328-4e8e-a96b-192a72b444f3" />

___
- Praticing yaml file with list and dictionary exercise
https://github.com/mmumshad/kubernetes-training-answers
<img width="355" height="414" alt="image" src="https://github.com/user-attachments/assets/17f8e718-b7ce-41e6-8c2d-b1d840ae9fdf" />

___
- Kubectl descibe pod to check pod details
<img width="1014" height="781" alt="image" src="https://github.com/user-attachments/assets/e7dd0d4e-b799-4fc2-9395-84c30b66c0af" />

___
- Created pod.yaml file and run it to create pod
<img width="624" height="303" alt="image" src="https://github.com/user-attachments/assets/c92f5be7-d94b-4578-af3a-1d5cf49c0414" />
<img width="503" height="34" alt="image" src="https://github.com/user-attachments/assets/5fc7f4de-68ab-42f2-bc50-2f2a43c9940c" />
<img width="447" height="91" alt="image" src="https://github.com/user-attachments/assets/bb1c8eae-2dcc-4e1d-9b6b-f2069d03b2e7" />

___
- Replication Controllers and ReplicaSets
- Created replicaset.yaml file and update the details in it
<img width="490" height="352" alt="image" src="https://github.com/user-attachments/assets/41f6db43-7820-4ce6-a6d7-d3203ec4b1e9" />
- kubectl apply -f replicaset.yaml
- kubectl get replicaset
- kubectl get pods
- Pods are up and running 
<img width="628" height="209" alt="image" src="https://github.com/user-attachments/assets/906f8b69-49e5-45e6-8d0b-cf0db045f790" />

___
- Deletted the pod and new pod came up automatically
- kubectl delete pod myapp-replicaset-lqfww
<img width="726" height="141" alt="image" src="https://github.com/user-attachments/assets/a2a30f83-59d8-4e22-b1a2-00e4970dc25c" />

___
- kubectl describe replicaset myapp-replicaset
<img width="824" height="425" alt="image" src="https://github.com/user-attachments/assets/534d8ea1-33a9-41ed-a679-dc4dfda59a7f" />
<img width="701" height="156" alt="image" src="https://github.com/user-attachments/assets/8a2eeba3-d7d5-430a-9754-dc37c49f3fb0" />

___
- Edited replicaset count
- kubectl edit replicaset myapp-replicaset
<img width="724" height="570" alt="image" src="https://github.com/user-attachments/assets/c361d060-768b-42ba-9249-e95daf0b0ea1" />
<img width="489" height="140" alt="image" src="https://github.com/user-attachments/assets/43755bd6-799e-48aa-bddf-40575885b6a8" />

___
- Created deployment file and run it
- kubectl create -f deployment.yaml
<img width="666" height="169" alt="image" src="https://github.com/user-attachments/assets/5ce1d6ec-eae1-405c-812b-5dbe27a32bda" />
<img width="686" height="454" alt="image" src="https://github.com/user-attachments/assets/f2d30678-c32e-4ddc-ad90-1713220ae860" />

- Kubectl describe deployments myapp-deployment
<img width="958" height="640" alt="image" src="https://github.com/user-attachments/assets/0c7225e2-c2d2-4969-8f60-2d7551917fc0" />
