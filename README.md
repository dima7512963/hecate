
### redis local

```bash
docker run --name some-redis -d -p 6379:6379  redis:5-alpine redis-server


 1051  docker build -t biovirt/centos7-erlang .
 1052  sudo docker push biovirt/centos7-erlang 

```


```erlang
wpool:call(redis, {q, ["SMEMBERS", "device:list"]}).
wpool:call(redis, {q, ["GET", "123"]}).
wpool:call(redis, {q, ["SET", "resource-name", "anystring",  "NX",  "EX",  "5"]}).
wpool:call(db, {q, "SELECT id, is_deleted FROM DEVICE"}, available_worker, 30000).

{ok, Pid} = device_mng:start_link(101601).
```




