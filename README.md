# jun-kubernetes

[Pods | Kubernetes](https://kubernetes.io/docs/concepts/workloads/pods/)

* kubernetes/pod/pod-1.yaml
* nginx
* kubernetes/job/job-1.yaml
* busybox, command

[kind – Quick Start](https://kind.sigs.k8s.io/docs/user/quick-start/#multinode-clusters)

* kind/kind-1.yaml
* multinode, multi-node

[Deploy a MySQL database server in Kubernetes - Static - DEV Community 👩‍💻👨‍💻](https://dev.to/musolemasu/deploy-a-mysql-database-server-in-kubernetes-static-dpc)

[Deploying MySQL on Kubernetes {Guide} | phoenixNAP KB](https://phoenixnap.com/kb/kubernetes-mysql)

[Run a Single-Instance Stateful Application | Kubernetes](https://kubernetes.io/docs/tasks/run-application/run-single-instance-stateful-application/)

* mysql/manifest/v8.0/
* persistentVolumeClaim, volumeMounts

[Attach Handlers to Container Lifecycle Events | Kubernetes](https://kubernetes.io/docs/tasks/configure-pod-container/attach-handler-lifecycle-event/)

* kubernetes/pod/lifecycle/lifecycle-1.yaml
* postStart, preStop, exec, command

[Configure Liveness, Readiness and Startup Probes | Kubernetes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/)

* kubernetes/pod/probe/probe-1.yaml
* busybox, livenessProbe, exec, command
* kubernetes/pod/probe/probe-2.yaml
* livenessProbe, httpGet
* kubernetes/pod/probe/probe-3.yaml
* readinessProbe, tcpSocket, livenessProbe
* kubernetes/pod/probe/probe-4.yaml
* etcd, command, livenessProbe, grpc
* kubernetes/pod/probe/probe-5.yaml
* startupProbe, httpGet
* kubernetes/pod/probe/probe-6.yaml
* busybox, readinessProbe, exec, command