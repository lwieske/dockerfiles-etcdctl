# Dockerfiles for etcdctl / {{ index (ds "versions") (math.Sub (len (ds "versions")) 1) }} - {{ index (ds "versions") 0 }}

[![](https://images.microbadger.com/badges/image/lwieske/etcdctl.svg)](https://microbadger.com/images/lwieske/etcdctl "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/lwieske/etcdctl.svg)](https://microbadger.com/images/lwieske/etcdctl "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/commit/lwieske/etcdctl.svg)](https://microbadger.com/images/lwieske/etcdctl "Get your own commit badge on microbadger.com")

## **Dockerfiles** for [etcdctl](https://kubernetes.io/docs/reference/etcdctl/etcdctl/) on [Alpine](https://registry.hub.docker.com/_/alpine/) for Docker Automated/Trusted Builds.

```
docker run -i -t lwieske/etcdctl 
```

***

{{ range (ds "versions") -}}
### {{.}}

| Image | Badge |
| ----- | ----- |
| lwieske/etcdctl:{{.}} | [![](https://images.microbadger.com/badges/image/lwieske/etcdctl:{{.}}.svg)](https://microbadger.com/images/lwieske/etcdctl:{{.}} "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/lwieske/etcdctl:{{.}}.svg)](https://microbadger.com/images/lwieske/etcdctl:{{.}} "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/commit/lwieske/etcdctl:{{.}}.svg)](https://microbadger.com/images/lwieske/etcdctl:{{.}} "Get your own commit badge on microbadger.com") |

{{end}}