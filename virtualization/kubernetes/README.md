# Kubernetes


[<img src="../../assets/k8s/k8s_logo.png" width="150"/>](../../assets/k8s/k8s_logo.png)

## 📘 Documentation
https://kubernetes.io/docs/home/

---

## ⚙️ Installation
### On Mac
```bash
brew install kubectl
```
### On Ubuntu
```bash
sudo apt-get update
sudo apt-get install -y ca-certificates curl
sudo curl -fsSLo /etc/apt/keyrings/kubernetes-archive-keyring.gpg https://packages.cloud.google.com/apt/doc/apt-key.gpg
echo "deb [signed-by=/etc/apt/keyrings/kubernetes-archive-keyring.gpg] https://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee /etc/apt/sources.list.d/kubernetes.list
sudo apt-get update
sudo apt-get install -y kubectl
```

### On Windows
```bash
choco install kubernetes-cli
```

Check the installation:
```bash
kubectl version --client
```

### Official installation guide
https://kubernetes.io/releases/download/

---

## 📚 Courses

CKA

[<img src="../../assets/k8s/k8s_cka_01.png" width="75%">](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/ "Udemy - CKA course")

CKAD

[<img src="../../assets/k8s/k8s_ckad_01.png" width="75%">](https://www.udemy.com/course/certified-kubernetes-application-developer/ "Udemy - CKAD course")

CKS

[<img src="../../assets/k8s/k8s_cks_01.png" width="75%">](https://www.udemy.com/course/certified-kubernetes-security-specialist/ "Udemy - CKS course")

---

## 🎯 Labs
KodeKloud

- https://kodekloud.com/

CKA

- https://kodekloud.com/courses/labs-certified-kubernetes-administrator-with-practice-tests/


CKAD

- https://kodekloud.com/courses/labs-certified-kubernetes-application-developer/

CKS

- https://killercoda.com/killer-shell-cks/

Game of Pods

- https://kodekloud.com/courses/kubernetes-challenges/

---

## ⏯️ Tutorials

- [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- [Introduction to Kubernetes](https://www.edx.org/course/introduction-to-kubernetes)
- [Hello Minikube](https://kubernetes.io/docs/tutorials/hello-minikube/)
- [Kubernetes Docs Tutorials](https://kubernetes.io/docs/tutorials/)
---

## ⏱️ Quickstart Guide
[TBD]

--- 

## 🎬 Videos
[TBD]

---

## 🌵 GitHub
https://github.com/kubernetes/kubernetes

---

## 🎓 Certifications

https://trainingportal.linuxfoundation.org/

---

## 🔖 Useful bookmarks for the exam

Rembember that you can keep a bookmarks' folder with all the following links to use during your exam (unless they are from the k8s forum):
- https://kubernetes.io/docs/reference/kubectl/cheatsheet/
- https://kubernetes.io/docs/concepts/workloads/controllers/deployment/
- https://kubernetes.io/docs/tasks/configure-pod-container/configure-persistent-volume-storage/
- https://kubernetes.io/docs/concepts/configuration/secret/
- https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/
- https://kubernetes.io/docs/concepts/workloads/controllers/job/
- https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/
- https://kubernetes.io/docs/concepts/services-networking/network-policies/
- https://kubernetes.io/docs/concepts/services-networking/ingress/
- https://kubernetes.io/docs/tasks/configure-pod-container/security-context/
- https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/
- https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/
- https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes-using-node-affinity/
- https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/
- https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands