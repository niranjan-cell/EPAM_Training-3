```
kubectl get pod : To list all the pods
kubectl run <pod_name> --image=<image_name> : To create the pod
kubectl describe <resource_type> <resource_name> :  To describe any resourse
kubectl get <resource_type> -o wide : To check the wide output
kubectl get <resource_type> <resource_name> -o yaml : To check the details about the resource in yaml format
kubectl get <resource_type> <resource_name> -o json : To check the details about the resource in json format
kubectl delete <resource_type> <resource_name> : To delete the specific resource
kubectl apply -f pod.yml : To create kubernetes resource in declarative way
kubectl delete -f pod.yml : To create kubernetes resource in declarative way
kubectl exec <pod_name> -- <command> : To run any command inside the pod
kubectl exec <pod_name> -c <container_name> -- <command> : To run any command inside the pod if it is a multi container pod
kubectl logs <pod_name> -f : TO check the logs of container if it is a single contianer pod
kubectl logs <pod_name> -c <container_name> -f : TO check the logs of container if it is a multi contianer pod
kubectl delete <resource_type> --all : TO delete all resource of specific type
kubectl delete all --all : To delete all resource
kubectl run myapp --image=nginx --dry-run=client : To dry run
kubectl run myapp --image=nginx --dry-run=client -o yaml > <file_name>.yml : To create resource from command line
```
