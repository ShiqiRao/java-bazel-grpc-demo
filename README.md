# java-bazel-grpc-demo

## Build
bazel build //...

## Deploy
bazel build //src/main/java/io/grpc/examples/helloworld:server_deploy.jar    

bazel build //src/main/java/io/grpc/examples/helloworld:client_deploy.jar

## Run
java -jar bazel-bin/src/main/java/io/grpc/examples/helloworld/server_deploy.jar

java -jar bazel-bin/src/main/java/io/grpc/examples/helloworld/client_deploy.jar

## Result
The client's terminal will display:
```text
Greeting: Hello world
```