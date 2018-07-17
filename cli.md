CLI for Amazon Redshift
---

# start cluster

```
aws redshift create-cluster --cluster-identifier sample-cluster \
--master-username redshift \
-- master-user-password Redshift123 \
--node-type dc1.large \
--cluster-type single node \
--profile myprofile
```

# stop cluster

