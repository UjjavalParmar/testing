### CLUSTER CREATION

* k exec -it redis-0 -n rc -- bash

* redis-cli --cluster create redis-0.redis.rc.svc.cluster.local:6379 redis-1.redis.rc.svc.cluster.local:6379 redis-2.redis.rc.svc.cluster.local:6379 redis-3.redis.rc.svc.cluster.local:6379 redis-4.redis.rc.svc.cluster.local:6379 redis-5.redis.rc.svc.cluster.local:6379 --cluster-replicas 1
