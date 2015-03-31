* Microservices
	* Resilience: use distributed systems patterns
	* Scaling
	* Ease of deployment
	* Organizational alignment
	* Composability
	* Optimize for repleceability

* HTTP
	* Clients should set User-Agent to be easy identifiable (ident + version)
	* Use transfer/representational patterns for REST APIs
	* HTTP/2

* Try other protocols:
	* Statically typed: Protocol Buffers, Thrift, XDR
	* Dynamically typed: JSON, Avro, MessagePack, BSON
	* https://github.com/alecthomas/go_serialization_benchmarks

* Patterns to test
	* Circuit breaker in clients

* Helpful Software
	* https://github.com/gregjones/httpcache
	* https://github.com/golang/groupcache
	* https://github.com/bradfitz/http2
	* https://github.com/peterbourgon/gokit
	* https://github.com/hashicorp/consul
	* https://github.com/coreos/etcd
	* https://github.com/koding/kite
	* https://github.com/asim/go-micro
	* https://github.com/gocircuit/circuit
	* https://github.com/rsms/gotalk
	* https://github.com/Sirupsen/logrus
	* https://github.com/afex/hystrix-go
	* https://github.com/armon/go-metrics
	* https://github.com/codahale/lunk
	* https://github.com/eapache/go-resiliency
	* https://github.com/FogCreek/logging
	* https://github.com/grpc/grpc-go
	* https://github.com/inconshreveable/log15
	* https://github.com/mailgun/vulcand
	* https://github.com/mattheath/phosphor
	* https://github.com/rubyist/circuitbreaker
	* https://github.com/sourcegraph/appdash
	* https://github.com/spacemonkeygo/monitor
	* https://github.com/streadway/handy

* Requirements
	* Monitoring
	* Versioning
	* Access-by-Reference
	* Follow business concepts