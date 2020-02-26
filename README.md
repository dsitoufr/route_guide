Description
___________

The route guide server and client demonstrate how to use grpc go libraries to perform unary, client streaming, server streaming and full duplex RPCs.

Please refer to gRPC Basics: Go for more information.

See the definition of the route guide service in routeguide/route_guide.proto.

Run the sample code
___________________

To compile and run the server, assuming you are in the root of the route_guide folder, i.e., .../examples/route_guide/, simply:

$ go run server/server.go

Likewise, to run the client:

$ go run client/client.go

Optional command line flags
___________________________

The server and client both take optional command line flags. For example, the client and server run without TLS by default. To enable TLS:

$ go run server/server.go -tls=true

and

$ go run client/client.go -tls=true