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
