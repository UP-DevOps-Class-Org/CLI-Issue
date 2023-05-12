# Common Issues

## strconv.Atoi: parsing "": invalid syntax

**Solution**

```
docker-compose down --remove-orphans
```
## Remove all docker images and containers
```
docker system prune -a
```
## Validate/Test the haproxy configuration,
```
docker run -it --rm --name haproxy-syntax-check haproxy-docker haproxy -c -f /usr/local/etc/haproxy/haproxy.cfg
```
## Open JMeter via terminal
```
open /usr/local/bin/jmeter
```
