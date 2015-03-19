* HTTP
	* Clients should set User-Agent to be easy identifiable (ident + version)
	* Use transfer/representational patterns for REST APIs
	* HTTP/2
		* Support (varnish, nginx, apache, etc)


* Try other protocols:
	* Statically typed: Protocol Buffers, Thrift, XDR
	* Dynamically typed: JSON, Avro, MessagePack, BSON
	* https://github.com/alecthomas/go_serialization_benchmarks


* Patterns to test
	* Circuit breaker in clients