# How to Run

---

* Clone this repo

```
git clone https://github.com/mhwong2007/Snorkel-Workshop.git
```

* Pull an image from docker hub and create a container, mount the path of the cloned repo to `/data`

```
docker create --name=snorkel_workshop \
-v /path/to/repo:/data \
-p 8888:8888 \
mhwong2007/snorkel_workshop:latest
```

* Start container

```
docker start snorkel_workshop
```

* Open `http://localhost:8888` on browser