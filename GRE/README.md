## R1

```
int tunnel 1
tunnel source 172.16.1.2
tunnel destin 172.17.1.2
ip addr 10.10.10.1 255.255.255.252

```


## R2
```
int tunnel 2
tunnel source 172.17.1.2
tunnel destin 172.16.1.2
ip addr 10.10.10.2 255.255.255.252
```
