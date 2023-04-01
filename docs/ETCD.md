---

created: ["02-04-23 00:54"]

aliases: ["ETCD"]

tags:

- CourseNote/etcd

---

  

---

# ❗ Topic

  - This is regarding ETCD highlevel

## 📦 Resources

- https://etcd.io/

## 🔑 Key Points

- distributed reliable key-value store that is Simple, Secure and Fast
- commands are different w.r.t versions of etcd
	- `./etcdctl`    -> will give all commands supported w.r.t versions

## ❓ Questions

- How to operate on ETCD?
- What's role of ETCD in k8s?

## 🎯 Actions

- Install ETCD
	- Download Binary
		- https://etcd.io/docs/v3.4/install/
	- Extract
		- tar xzvf 
	- Run ETCD Service
		-  ```./etcd```
		- it will start a service on default port 2379  
- Create entry in db
	-  ``./etcdctl set key1 value1``    -> ETCDCTL v2
	-  `./etcdctl put key1 value1`    -> ETCDCTL v3
- Retrive data
	- ``./etcdctl get key1

- Change ETCDCTL version
	- `./etcdctl --version`
	- `ETCDCTL_API=3 ./etcdctl version` or export to env

## 📃 Summary of Notes

-