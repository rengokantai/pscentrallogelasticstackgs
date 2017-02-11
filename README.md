# pscentrallogelasticstackgs
##3. Configuring Elasticsearch
###2 Installing Elasticsearch on Linux
check os version
```
cat /etc/issue.net
```
```
apt install openjdk-8-jre-headless
```
version 5.2, does not work for u16.10 1gb memory(tested)
```
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-5.2.0.deb
```
I personally use 2.4.1
```
wget https://download.elastic.co/elasticsearch/release/org/elasticsearch/distribution/deb/elasticsearch/2.4.1/elasticsearch-2.4.1.deb
```


```
sysctl -w vm.max_map_count=262144
```

###3. Installing Elasticsearch on Windows Server
```
Invoke-WebRequest -Uri http://192.168.1.1:9200
```

##4. Installing Logstash
###2
```
wget https://download.elastic.co/logstash/logstash/packages/debian/logstash-2.4.0_all.deb
```
