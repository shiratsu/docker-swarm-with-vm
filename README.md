# 参考にしてるもの

https://qiita.com/KuwaK/items/a72706e0de49adda2c7f

swarm vs ecs vs kubernetesの比較を見るくらいだから、同列のものなんだね

# コマンドhistory

## swarmモード初期化
```
docker swarm init --advertise-addr="192.168.33.10" --listen-addr=0.0.0.0:2377
```
ls
```
docker node ls
```

workerノードのjoin
```
docker swarm join --token SWMTKN-1-66qe5cyf31fd8rktwvjbrtpd63l32789aqpbfheauwgfh38g8wrf2ey-bob77wfdnrkpcmqtxfgkiu47a 192.168.33.10:2377

```
