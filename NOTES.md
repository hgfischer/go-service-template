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

* Helpful Packages
	* https://github.com/gregjones/httpcache
	* https://github.com/golang/groupcache
	* https://github.com/bradfitz/http2
	* https://github.com/peterbourgon/gokit

* Requirements
	* Monitoring
	* Versioning
	* Access-by-Reference
	* Follow business concepts