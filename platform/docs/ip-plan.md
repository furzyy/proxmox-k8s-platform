| Name        | Role          | vCPU | RAM | Disk | IP            | Hostname     |
| ----------- | ------------- | ---- | --- | ---- | ------------- | ------------ |
| k8s-control | control-plane | 2    | 4GB | 12GB | 192.168.1.130 | k8s-master   |
| k8s-node1   | worker        | 2    | 2GB | 8GB  | 192.168.1.131 | k8s-worker-1 |
| k8s-node2   | worker        | 2    | 2GB | 8GB  | 192.168.1.132 | k8s-worker-2 |
| prometheus  | monitoring    | 2    | 2GB | 8GB  | 192.168.1.133 | prometheus   |
| bastion     | tooling       | 1    | 1GB | 8GB  | 192.168.1.134 | bastion      |
