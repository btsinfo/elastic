curl -L -O https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-7.9.0-x86_64.rpm
rpm -vi elastic-agent-7.9.0-x86_64.rpm
xpack.ingestManager.enabled: true
xpack.ingestManager.fleet.tlsCheckDisabled: true 
xpack.security.enabled: true
elasticsearch.username: "elastic" 
elasticsearch.password: "abc123iUnbRftkABC123"
#gdhdgsqj
https://search.maven.org/remotecontent?filepath=co/elastic/apm/apm-agent-attach/1.18.0.RC1/apm-agent-attach-1.18.0.RC1-standalone.jar

java -jar apm-agent-attach-standalone.jar --pid 42 \
    --config service_name=my-cool-service server_urls=http://localhost:8200
