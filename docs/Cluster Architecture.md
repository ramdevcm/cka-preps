---

created: ["02-04-23 00:50"]

aliases: ["CKA"]

tags:

- CourseNote/k8sArchitecture

---

  

---

# ❗ Topic
This note is regarding k8s architecture
  

## 📦 Resources

  - [[k8sArchitecture.canvas]]

## 🔑 Key Points

- Master node is responsible to manage/contol/plan/schedule/monitor worker node
- Worker node hosts application as containers
- [[KubeApiServer]] is primary management component of k8s
- [[Scheduler]] acts as a crane in ship. It allocates required containers to worker nodes
- Controller-Manager
	- Node-Controller
	- Replication-Controller
- [[Kubelet]] - similar to captian of ship. It listens for instructions from [[KubeApiServer]] and deploys/destroys containers on node as required.
- [[Kube-proxy]] ensures that the necessary rules (for communication) are in place at worker nodes to allow containers running on them to reach out other containers.
## ❓ Questions

- 

## 🎯 Actions

- [ ]


## 📃 Summary of Notes

-