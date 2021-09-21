# helm-charts
** Charts for Kubernetes deployments ** </br>
---
1. hive-metastore </br>
2. trino </br>
3. superset </br>
4. flink </br>
5. hbase </br>

## Installation process 
---
```
helm repo add c1bcharts https://sbbagal13.github.io/helm-charts/ 

helm install hive-metastore c1bcharts/hive-metastore
helm install trino c1bcharts/trino` 
helm install superset c1bcharts/superset` 
helm install cstone-flink c1bcharts/flink`  
helm install cstone-hbase c1bcharts/hbase` 
```

Note: Chart name and release names can be replaced

## Search charts from repo (once after added to repo) 
---
`helm search repo hive-metastore` </br>
`helm search repo trino` </br> 
`helm search repo superset` </br> 
`helm search repo flink` </br> 
`helm search repo hbase` </br> 

