# helm-charts
### Charts for Kubernetes deployments  
---
1. hive-metastore 
2. trino 
3. superset 
4. flink 
5. hbase 

## Installation process 
---
```
helm repo add c1bcharts https://sbbagal13.github.io/helm-charts/ 

helm install hive-metastore c1bcharts/hive-metastore
helm install trino c1bcharts/trino 
helm install superset c1bcharts/superset 
helm install cstone-flink c1bcharts/flink  
helm install cstone-hbase c1bcharts/hbase 
```

Note: Chart name and release names can be replaced

## Search charts from repo (once after added to repo) 
---
```
helm search repo hive-metastore 
helm search repo trino 
helm search repo superse 
helm search repo flink  
helm search repo hbase  
```
