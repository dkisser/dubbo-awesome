```java
[INFO] Scanning for projects...
[WARNING] 
[WARNING] Some problems were encountered while building the effective model for org.apache.dubbo:benchmark-base:jar:1.0-SNAPSHOT
[WARNING] 'build.plugins.plugin.version' for org.codehaus.mojo:build-helper-maven-plugin is missing. @ line 120, column 21
[WARNING] 
[WARNING] It is highly recommended to fix these problems because they threaten the stability of your build.
[WARNING] 
[WARNING] For this reason, future Maven versions might no longer support building such malformed projects.
[WARNING] 
[INFO] ------------------------------------------------------------------------
[INFO] Detecting the operating system and CPU architecture
[INFO] ------------------------------------------------------------------------
[INFO] os.detected.name: linux
[INFO] os.detected.arch: x86_64
[INFO] os.detected.version: 5.15
[INFO] os.detected.version.major: 5
[INFO] os.detected.version.minor: 15
[INFO] os.detected.release: ubuntu
[INFO] os.detected.release.version: 22.04
[INFO] os.detected.release.like.ubuntu: true
[INFO] os.detected.release.like.debian: true
[INFO] os.detected.classifier: linux-x86_64
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Build Order:
[INFO] 
[INFO] benchmark-base                                                     [jar]
[INFO] server-base                                                        [jar]
[INFO] client-base                                                        [jar]
[INFO] dubbo-grpc-client                                                  [jar]
[INFO] 
[INFO] ------------------< org.apache.dubbo:benchmark-base >-------------------
[INFO] Building benchmark-base 1.0-SNAPSHOT                               [1/4]
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ benchmark-base ---
[INFO] Deleting /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target
[INFO] 
[INFO] --- protobuf-maven-plugin:0.6.1:compile (default) @ benchmark-base ---
[INFO] Building protoc plugin: dubbo-3
[INFO] Building protoc plugin: dubbo-grpc
[INFO] Compiling 1 proto file(s) to /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/generated-sources/protobuf/java
[INFO] 
[INFO] --- protobuf-maven-plugin:0.6.1:compile-custom (default) @ benchmark-base ---
[INFO] Building protoc plugin: dubbo-3
[INFO] Building protoc plugin: dubbo-grpc
[INFO] Compiling 1 proto file(s) to /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/generated-sources/protobuf/grpc-java
[INFO] 
[INFO] --- build-helper-maven-plugin:3.3.0:add-source (default) @ benchmark-base ---
[INFO] Source directory: /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/build/generated/source/proto/main/java added.
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ benchmark-base ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/src/main/resources
[INFO] Copying 1 resource
[INFO] Copying 1 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ benchmark-base ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 14 source files to /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/classes
[INFO] /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/generated-sources/protobuf/java/org/apache/dubbo/benchmark/bean/PagePB.java: /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/generated-sources/protobuf/java/org/apache/dubbo/benchmark/bean/PagePB.java uses or overrides a deprecated API.
[INFO] /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/generated-sources/protobuf/java/org/apache/dubbo/benchmark/bean/PagePB.java: Recompile with -Xlint:deprecation for details.
[INFO] 
[INFO] --- protobuf-maven-plugin:0.6.1:test-compile (default) @ benchmark-base ---
[INFO] /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/src/test/proto does not exist. Review the configuration or consider disabling the plugin.
[INFO] 
[INFO] --- protobuf-maven-plugin:0.6.1:test-compile-custom (default) @ benchmark-base ---
[INFO] /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/src/test/proto does not exist. Review the configuration or consider disabling the plugin.
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ benchmark-base ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ benchmark-base ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ benchmark-base ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ benchmark-base ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/benchmark-base/target/benchmark-base-1.0-SNAPSHOT.jar
[INFO] 
[INFO] --------------------< org.apache.dubbo:server-base >--------------------
[INFO] Building server-base 1.0-SNAPSHOT                                  [2/4]
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ server-base ---
[INFO] Deleting /home/runner/work/dubbo-awesome/dubbo-awesome/server-base/target
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ server-base ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 2 resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ server-base ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to /home/runner/work/dubbo-awesome/dubbo-awesome/server-base/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ server-base ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/server-base/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ server-base ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ server-base ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ server-base ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/server-base/target/server-base-1.0-SNAPSHOT.jar
[INFO] 
[INFO] --------------------< org.apache.dubbo:client-base >--------------------
[INFO] Building client-base 1.0-SNAPSHOT                                  [3/4]
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ client-base ---
[INFO] Deleting /home/runner/work/dubbo-awesome/dubbo-awesome/client-base/target
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ client-base ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 2 resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ client-base ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 3 source files to /home/runner/work/dubbo-awesome/dubbo-awesome/client-base/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ client-base ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/client-base/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ client-base ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ client-base ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ client-base ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/client-base/target/client-base-1.0-SNAPSHOT.jar
[INFO] 
[INFO] -----------------< org.apache.dubbo:dubbo-grpc-client >-----------------
[INFO] Building dubbo-grpc-client 1.0-SNAPSHOT                            [4/4]
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ dubbo-grpc-client ---
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ dubbo-grpc-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 1 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ dubbo-grpc-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ dubbo-grpc-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ dubbo-grpc-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ dubbo-grpc-client ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-dependency-plugin:3.1.0:copy-dependencies (copy-dependencies) @ dubbo-grpc-client ---
[INFO] Copying protobuf-java-3.16.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/protobuf-java-3.16.3.jar
[INFO] Copying protobuf-java-util-3.7.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/protobuf-java-util-3.7.1.jar
[INFO] Copying guava-20.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/guava-20.0.jar
[INFO] Copying error_prone_annotations-2.3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/error_prone_annotations-2.3.2.jar
[INFO] Copying gson-2.8.9.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/gson-2.8.9.jar
[INFO] Copying client-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/client-base-1.0-SNAPSHOT.jar
[INFO] Copying benchmark-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/benchmark-base-1.0-SNAPSHOT.jar
[INFO] Copying grpc-netty-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-netty-1.44.0.jar
[INFO] Copying grpc-core-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-core-1.44.0.jar
[INFO] Copying annotations-4.1.1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/annotations-4.1.1.4.jar
[INFO] Copying animal-sniffer-annotations-1.19.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/animal-sniffer-annotations-1.19.jar
[INFO] Copying netty-codec-http2-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-codec-http2-4.1.72.Final.jar
[INFO] Copying netty-common-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-common-4.1.72.Final.jar
[INFO] Copying netty-buffer-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-buffer-4.1.72.Final.jar
[INFO] Copying netty-transport-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-transport-4.1.72.Final.jar
[INFO] Copying netty-resolver-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-resolver-4.1.72.Final.jar
[INFO] Copying netty-codec-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-codec-4.1.72.Final.jar
[INFO] Copying netty-handler-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-handler-4.1.72.Final.jar
[INFO] Copying netty-tcnative-classes-2.0.46.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-tcnative-classes-2.0.46.Final.jar
[INFO] Copying netty-codec-http-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-codec-http-4.1.72.Final.jar
[INFO] Copying netty-handler-proxy-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-handler-proxy-4.1.72.Final.jar
[INFO] Copying netty-codec-socks-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-codec-socks-4.1.72.Final.jar
[INFO] Copying perfmark-api-0.23.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/perfmark-api-0.23.0.jar
[INFO] Copying grpc-netty-shaded-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-netty-shaded-1.44.0.jar
[INFO] Copying grpc-protobuf-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-protobuf-1.44.0.jar
[INFO] Copying grpc-api-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-api-1.44.0.jar
[INFO] Copying grpc-context-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-context-1.44.0.jar
[INFO] Copying jsr305-3.0.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jsr305-3.0.2.jar
[INFO] Copying proto-google-common-protos-2.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/proto-google-common-protos-2.0.1.jar
[INFO] Copying grpc-protobuf-lite-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-protobuf-lite-1.44.0.jar
[INFO] Copying grpc-stub-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-stub-1.44.0.jar
[INFO] Copying jmh-core-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jmh-core-1.21.jar
[INFO] Copying jopt-simple-4.6.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jopt-simple-4.6.jar
[INFO] Copying commons-math3-3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/commons-math3-3.2.jar
[INFO] Copying jmh-generator-annprocess-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jmh-generator-annprocess-1.21.jar
[INFO] Copying dubbo-3.1.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/dubbo-3.1.0.jar
[INFO] Copying spring-context-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-context-5.2.20.RELEASE.jar
[INFO] Copying spring-aop-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-aop-5.2.20.RELEASE.jar
[INFO] Copying spring-beans-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-beans-5.2.20.RELEASE.jar
[INFO] Copying spring-core-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-core-5.2.20.RELEASE.jar
[INFO] Copying spring-jcl-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-jcl-5.2.20.RELEASE.jar
[INFO] Copying spring-expression-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-expression-5.2.20.RELEASE.jar
[INFO] Copying spring-context-support-1.0.8.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-context-support-1.0.8.jar
[INFO] Copying javassist-3.28.0-GA.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/javassist-3.28.0-GA.jar
[INFO] Copying snakeyaml-1.29.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/snakeyaml-1.29.jar
[INFO] Copying fastjson-1.2.83.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/fastjson-1.2.83.jar
[INFO] Copying fastjson2-2.0.7.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/fastjson2-2.0.7.jar
[INFO] Copying netty-all-4.1.25.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-all-4.1.25.Final.jar
[INFO] Copying slf4j-api-1.7.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/slf4j-api-1.7.25.jar
[INFO] Copying logback-classic-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/logback-classic-1.2.3.jar
[INFO] Copying logback-core-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/logback-core-1.2.3.jar
[INFO] Copying commons-cli-1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/commons-cli-1.4.jar
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ dubbo-grpc-client ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/dubbo-grpc-client-1.0-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for benchmark-base 1.0-SNAPSHOT:
[INFO] 
[INFO] benchmark-base ..................................... SUCCESS [  3.623 s]
[INFO] server-base ........................................ SUCCESS [  0.381 s]
[INFO] client-base ........................................ SUCCESS [  0.712 s]
[INFO] dubbo-grpc-client .................................. SUCCESS [  0.620 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.715 s
[INFO] Finished at: 2023-01-24T06:08:04Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-grpc-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-grpc-client/target/dubbo-grpc-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 06:08:05.738 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.741 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.803 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.804 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.821 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.822 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.863 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.863 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.863 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.867 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.867 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.874 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.875 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.877 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.879 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:08:05.879 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.018 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:08:06.051 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:08:06.063 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:08:06.130 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.157 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.164 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.357 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:08:06.374 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.375 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.375 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.376 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.408 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.536 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:08:06.536 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:08:06.702 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.704 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.711 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.716 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.722 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.770 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.799 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2085&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540486763&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.799 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2085&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540486763&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.868 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.889 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2085&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540486763&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.891 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:08:06.900 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.400 ops/ms
# Warmup Iteration   2: 8.937 ops/ms
# Warmup Iteration   3: 9.813 ops/ms
Iteration   1: 10.118 ops/ms
Iteration   2: 10.038 ops/ms
Iteration   3: 06:09:07.010 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.015 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.015 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.015 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.015 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.023 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.023 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:07.024 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.032 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2085&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540486763&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.033 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.035 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.036 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2085&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.037 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.037 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2085&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540486763&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.037 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.037 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.037 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.038 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.039 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.039 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.039 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.039 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.041 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.041 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.041 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.041 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:09.047 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.059 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (10.022, 10.059, 10.118), stdev = 0.051
  CI (99.9%): [9.125, 10.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:10.905 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:09:10.910 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:10.973 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:10.974 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:10.992 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:10.993 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.037 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.037 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.038 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.042 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.042 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.049 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.049 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.052 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.054 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.054 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.191 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:09:11.224 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:09:11.236 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:09:11.325 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.341 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.342 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.555 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:09:11.571 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.571 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.572 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.572 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.590 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.715 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:09:11.716 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:09:11.889 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.891 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.906 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.911 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.913 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:11.965 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:12.011 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2465&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540551942&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:12.011 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2465&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540551942&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:12.129 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:09:12.144 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2465&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540551942&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:09:12.145 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:09:12.150 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
7.435 ops/ms
# Warmup Iteration   2: 10.119 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 06:10:12.256 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.260 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.264 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.264 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.265 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.266 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.267 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:12.268 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.277 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2465&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540551942&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.277 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.280 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.281 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2465&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.281 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.281 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2465&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540551942&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.281 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.281 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.282 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.282 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.283 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.284 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.288 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.288 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.289 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.289 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.289 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.289 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.289 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.290 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.291 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.291 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.291 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.291 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:14.296 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.515 ±(99.9%) 1.682 ops/ms [Average]
  (min, avg, max) = (10.416, 10.515, 10.598), stdev = 0.092
  CI (99.9%): [8.833, 12.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 06:10:16.084 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.087 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.129 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.131 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.149 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.149 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.192 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.193 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.193 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.197 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.198 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.205 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.205 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.207 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.209 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.210 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.349 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:10:16.382 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:10:16.395 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:10:16.478 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.486 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.487 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.715 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:10:16.748 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.748 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.748 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.749 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:16.899 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:10:16.900 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:10:17.066 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.068 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.075 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.081 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.083 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.113 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.155 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2638&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540617106&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.156 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2638&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540617106&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.226 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.238 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2638&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540617106&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.239 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:10:17.248 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
6.911 ops/ms
# Warmup Iteration   2: 10.025 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 10.021 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 06:11:17.365 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.372 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.372 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.373 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.373 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.374 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.375 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:17.376 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.386 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2638&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540617106&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.386 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.387 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.388 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2638&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.388 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.389 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2638&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540617106&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.389 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.389 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.389 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:19.396 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-32] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.154 ±(99.9%) 2.548 ops/ms [Average]
  (min, avg, max) = (10.021, 10.154, 10.300), stdev = 0.140
  CI (99.9%): [7.606, 12.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 06:11:21.179 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.182 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.224 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.225 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.243 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.243 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.285 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.285 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.285 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.289 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.290 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.296 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.297 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.299 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.301 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.302 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.471 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:11:21.511 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:11:21.535 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:11:21.650 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.677 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.679 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.872 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:11:21.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.890 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.890 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:21.910 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.041 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:11:22.041 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:11:22.223 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.225 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.232 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.237 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.240 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.267 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.288 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2758&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540682261&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.288 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2758&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540682261&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.351 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.363 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2758&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540682261&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.363 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:11:22.368 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
5.285 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 7.868 ops/ms
Iteration   1: 7.807 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 06:12:22.483 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.489 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.492 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.492 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.492 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.494 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.494 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:22.495 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.507 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2758&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540682261&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.507 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.508 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.509 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2758&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.509 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.509 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2758&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540682261&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.509 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.509 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.510 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.510 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.511 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.512 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.513 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.513 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.513 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.513 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.513 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:24.521 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
7.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.822 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (7.731, 7.822, 7.927), stdev = 0.099
  CI (99.9%): [6.024, 9.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 06:12:26.336 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.355 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.420 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.421 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.438 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.439 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.489 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.489 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.489 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.493 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.493 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.500 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.500 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.503 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.505 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.505 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.661 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:12:26.720 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:12:26.736 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:12:26.838 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.851 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:26.856 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.062 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:12:27.078 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.079 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.079 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.079 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.101 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.223 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:12:27.224 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:12:27.393 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.395 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.402 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.408 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.410 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.451 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.491 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2865&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540747445&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.492 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2865&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540747445&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.571 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.589 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2865&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540747445&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.591 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:12:27.596 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.518 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.008 ms/op
Iteration   2: 3.226 ±(99.9%) 0.001 ms/op
Iteration   3: 06:13:27.708 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.713 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.713 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.713 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.716 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.717 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.719 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:27.720 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.734 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2865&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540747445&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.734 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.740 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.743 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2865&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.743 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.744 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2865&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540747445&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.744 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.744 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.744 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.745 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.745 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.748 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:29.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
3.092 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.172 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.092, 3.172, 3.226), stdev = 0.070
  CI (99.9%): [1.886, 4.457] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 06:13:31.485 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.538 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.540 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.563 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.563 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.605 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.605 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.605 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.609 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.609 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.616 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.617 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.619 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.621 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.622 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.763 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:13:31.804 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:13:31.833 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:13:31.922 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.949 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:31.950 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.130 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:13:32.157 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.158 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.158 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.159 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.187 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.318 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:13:32.319 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:13:32.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.490 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.497 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.502 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.505 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.612 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.654 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2977&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540812595&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.655 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2977&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540812595&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.727 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.741 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2977&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540812595&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.742 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:13:32.747 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.162 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.001 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
Iteration   3: 06:14:32.851 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.859 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.860 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.860 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.860 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.861 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.862 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:32.863 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.874 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2977&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540812595&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.874 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.881 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.882 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2977&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.882 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.882 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2977&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540812595&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.882 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.882 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.882 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.883 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.884 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.884 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.884 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.885 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.885 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.885 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.885 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.885 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.885 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.886 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.886 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.886 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.886 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.886 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:34.888 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.123
2.974 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.060 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (2.974, 3.060, 3.114), stdev = 0.075
  CI (99.9%): [1.687, 4.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 06:14:36.640 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.643 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.697 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.699 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.717 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.718 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.762 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.762 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.763 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.767 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.767 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.774 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.775 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.777 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:36.934 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:14:36.970 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:14:36.983 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:14:37.055 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.082 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.083 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.312 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:14:37.337 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.338 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.338 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.339 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.362 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.492 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:14:37.492 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:14:37.674 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.676 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.683 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.689 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.691 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.762 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.807 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3080&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540877747&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.807 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3080&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540877747&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.851 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.863 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3080&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540877747&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.864 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:14:37.869 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.390 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.003 ms/op
Iteration   1: 3.178 ±(99.9%) 0.002 ms/op
Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
Iteration   3: 06:15:37.959 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.963 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.963 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.963 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.963 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.968 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.969 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:37.970 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.978 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3080&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540877747&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.978 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.981 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.982 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3080&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.982 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.982 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3080&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540877747&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.982 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.982 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.982 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.983 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.984 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.986 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.986 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.986 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.986 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.987 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.987 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.988 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.988 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.989 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.990 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.990 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.990 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.990 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:39.994 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.123
3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.161 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.123, 3.161, 3.181), stdev = 0.033
  CI (99.9%): [2.563, 3.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 06:15:41.820 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.823 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.871 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.873 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.898 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.898 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.941 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.942 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.942 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.946 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.946 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.954 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.954 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.956 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.958 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:15:41.958 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.102 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:15:42.136 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:15:42.149 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:15:42.239 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.266 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.268 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.474 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:15:42.494 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.495 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.495 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.496 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.514 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.637 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:15:42.637 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:15:42.810 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.812 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.819 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.824 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.826 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.889 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.934 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3188&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540942877&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:42.935 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3188&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540942877&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:43.002 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:15:43.020 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3188&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540942877&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:15:43.021 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:15:43.028 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
5.094 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.009 ms/op
Iteration   1: 4.073 ±(99.9%) 0.012 ms/op
Iteration   2: 4.102 ±(99.9%) 0.011 ms/op
Iteration   3: 06:16:43.152 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.156 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.157 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.157 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.157 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.159 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.161 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:43.164 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.172 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3188&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540942877&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.173 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.174 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.175 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3188&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.175 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.175 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3188&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674540942877&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.175 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.175 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.175 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.176 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.177 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.177 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.177 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.178 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.178 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.178 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.178 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.178 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.178 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.179 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.179 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.179 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.179 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.179 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:45.181 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.123
4.020 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (4.020, 4.065, 4.102), stdev = 0.042
  CI (99.9%): [3.301, 4.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 06:16:46.950 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:16:46.953 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.007 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.008 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.025 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.026 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.067 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.067 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.068 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.071 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.072 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.079 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.080 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.084 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b145a0f, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.241 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:16:47.299 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:16:47.311 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:16:47.381 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.406 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.406 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.629 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:16:47.654 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.655 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.655 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.656 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.684 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:47.807 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:16:47.808 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:16:48.043 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.045 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.061 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.068 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.073 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.152 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.193 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3305&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541008134&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.193 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3305&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541008134&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.277 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3305&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541008134&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:16:48.285 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.310 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.156 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.145 ms/op
                 createUser·p0.9999: 18.645 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.068 ms/op
                 createUser·p0.9999: 16.043 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 06:17:49.233 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.238 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.238 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.239 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.239 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.241 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.242 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:49.245 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.257 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3305&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541008134&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.257 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.259 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3305&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3305&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541008134&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.261 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.262 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.262 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.262 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.262 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.264 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.264 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.264 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.264 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:51.265 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b145a0f, dubbo version: 3.1.0, current host: 10.1.0.123
3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 18.117 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305086
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 514 
    [ 1.250,  2.500) = 22062 
    [ 2.500,  3.750) = 249505 
    [ 3.750,  5.000) = 31780 
    [ 5.000,  6.250) = 584 
    [ 6.250,  7.500) = 278 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.083 ms/op
     p(99.9900) =     18.333 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 06:17:53.103 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.107 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.174 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.175 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.192 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.193 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.234 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.235 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.235 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.239 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.239 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.246 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.246 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.248 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.250 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.250 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6e472f23, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.390 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:17:53.441 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:17:53.454 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:17:53.559 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.586 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.586 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.778 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:17:53.794 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.794 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.794 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.795 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.813 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:53.937 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:17:53.938 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:17:54.110 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.111 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.119 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.125 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.152 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.197 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.216 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541074190&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.217 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541074190&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.257 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.267 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541074190&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.268 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:17:54.273 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.078 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.224 ms/op
                 existUser·p0.999:  7.560 ms/op
                 existUser·p0.9999: 20.205 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.361 ms/op
                 existUser·p0.9999: 15.531 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   3: 06:18:54.722 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.726 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.727 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.727 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.727 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.733 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.734 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:54.735 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.746 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541074190&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.746 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.748 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.750 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3411&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.750 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.750 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541074190&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.750 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.750 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.750 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.751 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.752 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.752 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.753 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.753 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.758 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.758 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.758 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.758 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.758 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.759 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.759 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.759 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.759 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.759 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:56.765 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6e472f23, dubbo version: 3.1.0, current host: 10.1.0.123
3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.208 ms/op
                 existUser·p0.9999: 25.690 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313683
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35045 
    [ 2.500,  5.000) = 277776 
    [ 5.000,  7.500) = 532 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     23.536 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 06:18:58.660 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.664 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.724 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.725 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.744 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.745 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.790 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.791 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.792 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.800 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.801 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.811 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.811 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.813 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.815 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.816 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:58.957 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:18:58.990 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:18:59.003 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:18:59.101 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.126 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.127 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.321 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:18:59.340 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.341 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.341 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.342 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.359 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.487 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:18:59.488 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:18:59.655 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.657 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.665 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.671 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.673 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.720 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3519&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541139712&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3519&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541139712&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.784 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.795 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3519&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541139712&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.796 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:18:59.804 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
4.318 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.323 ms/op
                 getUser·p0.9999: 17.496 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.241 ms/op
                 getUser·p0.9999: 18.415 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 06:20:00.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.400 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.401 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.401 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.401 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.402 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.403 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:00.404 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.414 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3519&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541139712&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.415 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.416 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3519&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3519&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541139712&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.418 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.419 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.420 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.420 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.420 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.421 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.421 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.422 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.423 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.423 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.424 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.424 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.424 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.424 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.424 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:02.427 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.123
3.184 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.685 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301023
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19707 
    [ 2.500,  5.000) = 280241 
    [ 5.000,  7.500) = 594 
    [ 7.500, 10.000) = 289 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.457 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 06:20:04.270 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.275 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.342 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.343 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.362 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.362 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.406 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.406 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.406 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.410 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.410 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.417 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.418 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.420 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.422 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.423 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4dd0f251, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.561 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:20:04.594 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:20:04.606 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:20:04.706 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.730 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.731 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.924 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:20:04.940 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.941 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.941 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.941 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:04.959 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.084 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:20:05.084 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.123
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
06:20:05.259 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.261 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.268 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.273 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.276 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.305 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.342 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3624&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541205298&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.343 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3624&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541205298&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.386 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.398 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3624&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541205298&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.399 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.123
06:20:05.404 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.123
6.112 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.837 ms/op
                 listUser·p0.9999: 21.500 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.502 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 06:21:05.862 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.866 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.866 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.867 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.867 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.868 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.868 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:05.869 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.123:20881, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.885 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.123:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3624&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541205298&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.886 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.887 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3624&protocol=grpc&register.ip=10.1.0.123&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.123&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3624&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674541205298&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.888 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.889 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.890 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.892 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.896 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.896 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.896 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.896 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.896 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.123
06:21:07.898 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-31] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4dd0f251, dubbo version: 3.1.0, current host: 10.1.0.123
4.163 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.534 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  17.533 ms/op
                 listUser·p0.9999: 28.941 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234964
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2349 
    [ 2.500,  5.000) = 200906 
    [ 5.000,  7.500) = 30245 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     26.493 ms/op
     p(99.9990) =     29.377 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.059 ± 0.934  ops/ms
ClientGrpc.existUser                       thrpt       3  10.515 ± 1.682  ops/ms
ClientGrpc.getUser                         thrpt       3  10.154 ± 2.548  ops/ms
ClientGrpc.listUser                        thrpt       3   7.822 ± 1.797  ops/ms
ClientGrpc.createUser                       avgt       3   3.172 ± 1.285   ms/op
ClientGrpc.existUser                        avgt       3   3.060 ± 1.373   ms/op
ClientGrpc.getUser                          avgt       3   3.161 ± 0.598   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.764   ms/op
ClientGrpc.createUser                     sample  305086   3.148 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.424           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.083           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.333           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  313683   3.058 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.594           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.536           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.345           ms/op
ClientGrpc.getUser                        sample  301023   3.188 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.706           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.282           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.921           ms/op
ClientGrpc.listUser                       sample  234964   4.087 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.534           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.493           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622           ms/op
```
