---

created: ["02-04-2023 23:21"]

aliases: ["Controller-Manager"]

tags:

- CourseNote/

---

  

---

# ❗ Topic

- Controller manager will be discussed in this note.
- Will cover
	- node controller
	- replica controller

## 📦 Resources

- Controller is a process that continously monitors the satte of system and works towards bringing all ships to desired state

## 🔑 Key Points

- It's like an office in master ship.
	- necessary actions will be taken from this office when new ship arrives/leaves/destroys
- It can also manage containers of ships. 
- 

## ❓ Questions

- 

## 🎯 Actions

- Node Controller
	- Watch ststus of node every 5s
	- If the heallth check fails for 40s, the node is marked as unreachable
	- After the node is marked as unreachable, it gives 5m for the node to come back.
		- If this fails, it removes the pods from this nod and assign them to health node.
		- ![[Pasted image 20230402233204.png]]

- Replication Controller
	 - Same happens with replica set


## 📃 Summary of Notes

