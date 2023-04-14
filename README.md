MY-PROJECT
---------------------
The project is a POC study and consists of the deployment model of the netjs application as end2end to the test and production namespaces installed on minikube k8s.
- EC2 server installed on AWS.
- Minikube, docker, k8s, argocd installations on the server have been completed.
- Github CI & Argo CD opensource tool was used for CI / CD process.
- It's set to trigger when push to Github test and prod(main) branches in CI step.
- Helm chart structure was used with Argo, the k8s deployment model.
- The private docker hub repository was used for the image repository and the Secret information was kept on the cluster.
