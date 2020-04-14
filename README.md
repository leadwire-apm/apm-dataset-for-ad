# apm-dataset-for-ad

Apm data is in json file format, you have to index manually :
1. install apm-server (see oss version in https://www.elastic.co/fr/downloads/past-releases)
2. setup the apm index template (https://www.elastic.co/guide/en/apm/server/current/apm-server-configuration.html)

```apm-server setup --template```

3. install logstash (see oss version in https://www.elastic.co/fr/downloads/past-releases)
4. configure a logstash pipeline (see https://github.com/leadwire-apm/apm-dataset-for-ad/blob/master/specjweb2018/logstash-pipeline.conf)
5. start logstash

