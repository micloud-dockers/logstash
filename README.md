# logstash

This is a logstash installed image base on debian.

## Use

```
docker run -it peihsinsu/logstash bash
```

## Use logstash

```
logstash -e "input { stdin { } } output { stdout {} }"
```


