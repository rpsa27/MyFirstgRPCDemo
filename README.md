# cd to the project folder
cd C:\Training\gRPC\Workspace\grpc-hello-server

to start the server: mvn exec:java -Dexec.mainClass=com.example.grpc.App

to start the client : mvn exec:java -Dexec.mainClass=com.example.grpc.Client

grpc-dump --port=8083 > gRPCtraffic.dump


References: 

Building a gRPC server/client : https://codelabs.developers.google.com/codelabs/cloud-grpc-java/index.html?index=..%2F..index#2

grpc-tools: https://github.com/bradleyjkemp/grpc-tools

capture traffic with wireshark: https://bkubiak.github.io/grpc-raw-requests/

grpc-java-examples: https://github.com/saturnism/grpc-by-example-java




