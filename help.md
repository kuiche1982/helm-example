```
$ helm package docs/examples/alpine/
$ mkdir fantastic-charts
$ mv alpine-0.1.0.tgz fantastic-charts/
$ helm repo index fantastic-charts --url https://fantastic-charts.storage.googleapis.com
```