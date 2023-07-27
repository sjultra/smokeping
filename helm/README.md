```
helm package smokeping-chart

```


```
helm install smokeping smokeping-chart-0.1.0.tgz --create-namespace --namespace smokeping
```