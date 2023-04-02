---

created: ["02-04-2023 23:37"]

aliases: ["Kube-Scheduler"]

tags:

- CourseNote/

---

  

---

# ❗ Topic

- Kube-Scheduler is responsible for scheduling pods on nodes based on certain criteria. 

## 📦 Resources

- ![[Pasted image 20230402234319.png]] Placing right container on right ship is the duty of scheduler

## 🔑 Key Points

-

## ❓ Questions

- Why do we need a scheduler?
	- When many ships are there, we need to schedule containers on right ship which should be travelled to right destinantion

## 🎯 Actions

- Filter Nodes
	- ![[Pasted image 20230402234507.png]]
	- Scheduler filters the node based on the required capacity. Here, we got two nodes with capacity of CPU > 10. Now we need to rank the nodes
- Rank Nodes
	- Uses prioroty func to assign score
	- 👀![[Pasted image 20230402234705.png]]
	- It used last node as it again has 6 CPU

##  👀 More Later...
- Resource Requirements & Limits
- Taints and Toleration
- Node Selector/Affinity

