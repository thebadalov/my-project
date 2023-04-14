MY-PROJECT
---------------------
First WAY
---------------------
The project is a POC study and consists of the deployment model of the netjs application as end2end to the test and production namespaces installed on minicube.
- EC2 server installed on AWS.
- Minikube, docker, k8s, argocd installations on the server have been completed.
- Github CI & Argo CD opensource tool was used for CI / CD process.
- It's set to trigger when push to Github branches in CI step.
- Helm chart structure was used with Argo, the k8s deployment model.
- The private docker hub repository was used for the image repository and the Secret information was kept on the cluster.
---------------------
Second WAY
---------------------
- I used open source Jenkins tool for CI/CD operation.
- In the same way I used ArgoCD for CD and I triggered from JenkinsfileDeploy Pipeline
- I used this way for production CI/CD path.
