## Generate self-signed certifactes

```
docker-compose -f create-certs.yml run --rm create_certs
```
## Increase virtual memory
You may get an error that says it's not enough virtual memory. Then this info may get in handy.

Ubuntu

```
sysctl -w vm.max_map_count=262144
```