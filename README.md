# helm-charts
Charts for Kubernetes deployments </br>
1) hive-metastore </br>
2) trino </br>
3) superset </br>

## Installation process 
`helm repo add customcharts https://sbbagal13.github.io/helm-charts/ ` </br>
`helm install hive-metastore customcharts/hive-metastore` </br>
`helm install trino customcharts/trino` </br> 
`helm install superset customcharts/superset` </br> 

Note: Chart name and release names can be replaced

## Search charts from repo (once after added to repo) 
`helm search repo hive-metastore` </br>
`helm search repo trino` </br> 
`helm search repo superset` </br> 

