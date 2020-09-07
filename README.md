# golang-http           

CNB Build Packs
--- 
```
git clone https://github.com/ozhankaraman/jx-go
cd jx-go
pack build jx-go --builder cloudfoundry/cnb:tiny
docker run --name jx-go --rm -it -p 8080:8080 jx-go:latest
```

* https://hub.docker.com/r/cloudfoundry/cnb
