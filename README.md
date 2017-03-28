# knockd-iptables
usage:
```bash
docker run --net=host --privileged --name knockd -d golendo/knockd SEQUENCE PORT INTERFACE
```

example:
```bash
docker run --net=host --privileged --name knockd -d golendo/knockd 7000,8000,9000 22 eth0
```
