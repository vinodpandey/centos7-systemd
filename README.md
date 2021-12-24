




## CentOS 7 with systemd enabled

running container
```
docker run -d --privileged --name httpd -v /sys/fs/cgroup:/sys/fs/cgroup:ro -p 80:80 vinodpandey/systemd:7.9.2009

docker exec -it httpd bash
systemctl status


```




