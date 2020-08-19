curl -L -O https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-7.9.0-x86_64.rpm
rpm -vi elastic-agent-7.9.0-x86_64.rpm
xpack.ingestManager.enabled: true
xpack.ingestManager.fleet.tlsCheckDisabled: true 
xpack.security.enabled: true
elasticsearch.username: "elastic" 
elasticsearch.password: "abc123iUnbRftkABC123"
