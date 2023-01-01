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
[INFO] benchmark-base ..................................... SUCCESS [  3.866 s]
[INFO] server-base ........................................ SUCCESS [  0.539 s]
[INFO] client-base ........................................ SUCCESS [  0.721 s]
[INFO] dubbo-grpc-client .................................. SUCCESS [  0.383 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.906 s
[INFO] Finished at: 2023-01-01T06:07:56Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-grpc-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-grpc-client/target/dubbo-grpc-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 06:07:57.180 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.185 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.233 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.253 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.254 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.301 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.302 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.302 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.306 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.307 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.314 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.315 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.317 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.320 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.320 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.493 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:07:57.550 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:07:57.563 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:07:57.670 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.685 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.688 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.908 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:07:57.931 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.931 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.931 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:57.966 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.104 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:07:58.104 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:07:58.296 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.298 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.306 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.312 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.315 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.349 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.395 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2089&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553278340&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.396 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2089&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553278340&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.506 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.522 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2089&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553278340&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.523 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:07:58.529 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
3.372 ops/ms
# Warmup Iteration   2: 6.633 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.762 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 06:08:58.649 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.653 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.654 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.654 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.654 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.659 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.659 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:08:58.661 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.671 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2089&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553278340&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.672 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.675 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2089&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.677 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2089&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553278340&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.677 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.677 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.677 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.678 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.679 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.679 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.680 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.680 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.681 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.681 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.681 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.681 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:00.684 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
9.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.872 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (8.762, 8.872, 9.012), stdev = 0.128
  CI (99.9%): [6.544, 11.201] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:02.691 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.695 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.744 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.745 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.766 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.767 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.816 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.816 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.816 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.821 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.821 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.829 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.829 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.832 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.835 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.835 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:02.994 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:09:03.031 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:09:03.046 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:09:03.130 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.162 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.163 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.443 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:09:03.474 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.481 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.481 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.482 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.515 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.676 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:09:03.676 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:09:03.900 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.902 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.920 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.933 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:03.938 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.003 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.049 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553343991&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.050 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553343991&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.145 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.159 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553343991&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.161 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:09:04.166 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
6.201 ops/ms
# Warmup Iteration   2: 8.606 ops/ms
# Warmup Iteration   3: 9.279 ops/ms
Iteration   1: 9.190 ops/ms
Iteration   2: 8.843 ops/ms
Iteration   3: 06:10:04.284 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.288 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.292 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.293 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.293 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.295 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.295 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:04.296 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.311 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553343991&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.311 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.315 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.316 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2411&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.316 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.316 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2411&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553343991&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.316 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.316 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.316 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.318 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.319 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.321 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.321 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.321 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.321 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.321 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.321 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:06.324 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-15] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
9.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.021 ±(99.9%) 3.167 ops/ms [Average]
  (min, avg, max) = (8.843, 9.021, 9.190), stdev = 0.174
  CI (99.9%): [5.853, 12.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 06:10:08.200 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.204 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.254 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.256 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.277 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.278 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.327 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.328 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.328 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.332 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.333 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.340 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.341 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.343 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.345 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.346 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.518 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:10:08.555 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:10:08.572 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:10:08.673 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.694 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.699 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.921 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:10:08.938 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.939 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.939 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.944 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:08.980 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.134 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:10:09.136 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:10:09.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.394 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.414 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.421 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.426 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.490 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.540 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2593&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553409474&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.540 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2593&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553409474&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.636 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.654 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2593&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553409474&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.655 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:10:09.663 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
5.883 ops/ms
# Warmup Iteration   2: 8.468 ops/ms
# Warmup Iteration   3: 8.686 ops/ms
Iteration   1: 8.825 ops/ms
Iteration   2: 8.725 ops/ms
Iteration   3: 06:11:09.799 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.806 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.807 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.807 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.807 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.808 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.809 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:09.810 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.823 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2593&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553409474&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.823 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.824 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.825 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2593&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2593&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553409474&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.828 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.828 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.828 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.828 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.830 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.830 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.830 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.830 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.830 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:11.831 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
8.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.779 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (8.725, 8.779, 8.825), stdev = 0.051
  CI (99.9%): [7.857, 9.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 06:11:13.749 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.753 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.802 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.803 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.823 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.824 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.873 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.873 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.873 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.878 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.878 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.886 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.886 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.889 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:11:13.892 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@33b0b6f9, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.060 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:11:14.097 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:11:14.111 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:11:14.246 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.274 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.280 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.521 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:11:14.539 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.542 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.542 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.543 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.564 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.711 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:11:14.712 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:11:14.951 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.963 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.974 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.980 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:14.986 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.050 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.097 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2720&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553475033&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.099 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2720&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553475033&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.219 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.232 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2720&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553475033&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.234 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:11:15.243 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
4.524 ops/ms
# Warmup Iteration   2: 6.349 ops/ms
# Warmup Iteration   3: 6.906 ops/ms
Iteration   1: 6.846 ops/ms
Iteration   2: 6.910 ops/ms
Iteration   3: 06:12:15.353 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.358 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.362 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.362 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.362 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.364 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.367 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:15.368 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.384 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2720&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553475033&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.384 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.391 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.392 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2720&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.393 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.393 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2720&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553475033&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.393 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.393 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.393 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.394 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.395 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.395 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.395 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.396 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.396 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.396 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.396 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.396 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.396 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.397 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.397 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.397 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.397 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.397 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:17.402 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@33b0b6f9, dubbo version: 3.1.0, current host: 10.1.0.124
6.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.916 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (6.846, 6.916, 6.993), stdev = 0.073
  CI (99.9%): [5.578, 8.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 06:12:19.275 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.279 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.330 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.331 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.352 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.402 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.402 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.402 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.407 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.407 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.418 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.421 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.421 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.602 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:12:19.646 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:12:19.682 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:12:19.806 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.851 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:19.853 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.064 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:12:20.081 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.103 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.251 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:12:20.252 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:12:20.486 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.488 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.502 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.516 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.521 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.608 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.662 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2830&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553540594&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.663 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2830&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553540594&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.744 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.761 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2830&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553540594&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.762 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:12:20.771 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
5.313 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.007 ms/op
Iteration   1: 3.637 ±(99.9%) 0.002 ms/op
Iteration   2: 3.608 ±(99.9%) 0.003 ms/op
Iteration   3: 06:13:20.896 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.905 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.905 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.905 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.905 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.907 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.908 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:20.910 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.919 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2830&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553540594&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.920 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.925 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.926 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2830&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.926 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.926 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2830&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553540594&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.926 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.927 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.927 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.928 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.931 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:22.938 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-31] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
3.701 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.649 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.608, 3.649, 3.701), stdev = 0.047
  CI (99.9%): [2.786, 4.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 06:13:24.812 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.815 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.864 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.866 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.888 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.889 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.962 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.962 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.962 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.967 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.967 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.975 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.975 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.978 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.980 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:13:24.981 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@feafb32, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.157 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:13:25.195 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:13:25.209 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:13:25.338 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.346 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.347 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.591 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:13:25.608 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.608 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.609 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.609 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.630 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.771 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:13:25.771 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:13:25.982 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:25.987 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.000 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.006 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.011 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.078 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.126 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2937&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553606063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.127 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2937&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553606063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.222 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.238 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2937&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553606063&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.239 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:13:26.244 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
4.869 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.004 ms/op
Iteration   1: 3.565 ±(99.9%) 0.002 ms/op
Iteration   2: 3.413 ±(99.9%) 0.003 ms/op
Iteration   3: 06:14:26.386 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.390 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.390 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.390 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.391 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.392 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.392 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:26.393 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.400 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2937&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553606063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.401 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.405 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.406 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2937&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.406 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.407 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2937&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553606063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.407 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.407 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.407 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.408 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.409 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.416 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.418 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.418 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.418 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.418 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.418 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.419 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:28.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@feafb32, dubbo version: 3.1.0, current host: 10.1.0.124
3.525 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.501 ±(99.9%) 1.441 ms/op [Average]
  (min, avg, max) = (3.413, 3.501, 3.565), stdev = 0.079
  CI (99.9%): [2.060, 4.942] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 06:14:30.317 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.322 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.384 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.386 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.406 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.406 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.455 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.456 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.456 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.460 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.461 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.469 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.469 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.471 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.474 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.474 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.635 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:14:30.675 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:14:30.690 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:14:30.791 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.821 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:30.822 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.049 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:14:31.067 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.067 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.067 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.068 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.118 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.267 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:14:31.268 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:14:31.466 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.468 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.476 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.482 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.485 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.602 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3041&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553671546&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.602 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3041&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553671546&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.687 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.707 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3041&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553671546&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.709 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:14:31.715 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
5.222 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.003 ms/op
Iteration   1: 3.553 ±(99.9%) 0.004 ms/op
Iteration   2: 3.570 ±(99.9%) 0.003 ms/op
Iteration   3: 06:15:31.821 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.837 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.838 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:31.839 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.851 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3041&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553671546&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.852 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.855 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.856 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3041&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.857 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.857 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3041&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553671546&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.857 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.857 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.857 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.858 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.859 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.860 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.860 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.860 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.860 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.861 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.861 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.861 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.861 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.862 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.862 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.862 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.862 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.862 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:33.871 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
3.679 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.601 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.553, 3.601, 3.679), stdev = 0.068
  CI (99.9%): [2.361, 4.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 06:15:35.756 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.759 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.820 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.822 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.848 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.849 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.898 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.901 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.902 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.912 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.912 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.920 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.921 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.923 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.926 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:15:35.926 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.084 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:15:36.122 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:15:36.137 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:15:36.230 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.238 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.239 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.468 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:15:36.487 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.487 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.488 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.488 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.510 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.651 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:15:36.652 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:15:36.906 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.908 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.924 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.932 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.937 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:36.997 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:37.042 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3221&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553736986&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:37.043 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3221&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553736986&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:37.163 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:15:37.180 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3221&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553736986&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:15:37.181 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:15:37.187 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
6.828 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.721 ±(99.9%) 0.013 ms/op
Iteration   1: 4.666 ±(99.9%) 0.007 ms/op
Iteration   2: 4.487 ±(99.9%) 0.007 ms/op
Iteration   3: 06:16:37.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.319 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.319 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.320 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.320 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.324 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.325 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:37.326 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.342 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3221&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553736986&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.343 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.345 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.345 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3221&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3221&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553736986&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.347 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.348 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.348 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.348 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.348 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.348 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.349 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.349 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.349 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.349 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.349 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.350 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.350 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.350 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.350 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:39.355 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-15] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
4.581 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.578 ±(99.9%) 1.633 ms/op [Average]
  (min, avg, max) = (4.487, 4.578, 4.666), stdev = 0.090
  CI (99.9%): [2.945, 6.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 06:16:41.209 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.212 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.261 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.283 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.284 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.332 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.333 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.333 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.337 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.338 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.346 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.346 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.348 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.351 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.351 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.515 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:16:41.568 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:16:41.584 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:16:41.663 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.687 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.688 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.902 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:16:41.919 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.920 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.920 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.920 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:41.940 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.083 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:16:42.083 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:16:42.277 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.286 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.292 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.295 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.330 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.368 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3331&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553802321&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.369 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3331&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553802321&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.416 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.429 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3331&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553802321&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.430 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:16:42.439 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
5.233 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.009 ms/op
Iteration   1: 3.676 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 15.181 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 3.670 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  14.221 ms/op
                 createUser·p0.9999: 17.629 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 06:17:43.249 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.255 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.256 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.256 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.256 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.260 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:43.261 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.274 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3331&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553802321&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.275 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.277 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3331&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3331&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553802321&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.279 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.280 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.281 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.281 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.281 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.281 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.282 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.282 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.282 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.282 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.283 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.283 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.283 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.283 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.283 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:45.288 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
3.695 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  15.081 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260806
  mean =      3.680 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 7908 
    [ 2.500,  3.750) = 138820 
    [ 3.750,  5.000) = 109364 
    [ 5.000,  6.250) = 3748 
    [ 6.250,  7.500) = 404 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 85 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =     11.023 ms/op
     p(99.9900) =     17.692 ms/op
     p(99.9990) =     18.920 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 06:17:47.220 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.224 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.293 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.295 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.317 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.317 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.372 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.372 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.373 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.386 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.386 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.401 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.403 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.406 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.412 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.412 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.598 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:17:47.635 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:17:47.669 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:17:47.770 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.792 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:47.797 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.012 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:17:48.029 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.030 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.030 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.031 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.051 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.203 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:17:48.204 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:17:48.425 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.427 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.436 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.442 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.445 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.479 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.503 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3441&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553868471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.504 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3441&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553868471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.586 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.605 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3441&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553868471&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.607 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:17:48.614 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
4.530 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.007 ms/op
Iteration   1: 3.507 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  7.629 ms/op
                 existUser·p0.9999: 16.495 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 3.440 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  7.692 ms/op
                 existUser·p0.9999: 17.848 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 06:18:49.200 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.205 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.206 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.206 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.206 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.208 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.209 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:49.212 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.225 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3441&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553868471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.226 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.226 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.227 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3441&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.227 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.228 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3441&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553868471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.228 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.228 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.228 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.229 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.230 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.230 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.230 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.230 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.231 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.231 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.231 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.231 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.231 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.232 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.232 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.232 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.232 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.232 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:51.239 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
3.477 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.183 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 33.923 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276167
  mean =      3.475 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15253 
    [ 2.500,  5.000) = 258538 
    [ 5.000,  7.500) = 2103 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     32.072 ms/op
     p(99.9990) =     34.356 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 06:18:53.194 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.213 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.275 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.277 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.299 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.300 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.350 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.350 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.350 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.355 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.356 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.363 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.364 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.366 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.369 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.370 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@244f3d31, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.532 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:18:53.570 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:18:53.585 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:18:53.690 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.705 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.705 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.947 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:18:53.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.966 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.966 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:53.987 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.142 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:18:54.143 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:18:54.436 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.438 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.453 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.463 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.469 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.523 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.547 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3546&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553934509&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.547 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3546&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553934509&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.595 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.612 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3546&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553934509&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.613 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:18:54.620 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
5.147 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.009 ms/op
Iteration   1: 3.706 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  13.107 ms/op
                 getUser·p0.9999: 14.543 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 3.610 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  7.813 ms/op
                 getUser·p0.9999: 16.255 ms/op
                 getUser·p1.00:   16.679 ms/op

Iteration   3: 06:19:55.494 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.499 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.499 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.499 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.500 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.501 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.502 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:55.503 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.510 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3546&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553934509&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.511 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.512 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.513 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3546&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.513 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.513 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3546&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672553934509&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.513 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.513 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.514 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.515 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.515 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.516 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.516 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.516 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.516 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.517 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.517 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.517 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.517 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.519 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.520 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.520 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.520 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.520 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:19:57.522 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-24] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@244f3d31, dubbo version: 3.1.0, current host: 10.1.0.124
3.658 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.240 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 24.165 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262386
  mean =      3.658 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5445 
    [ 2.500,  5.000) = 252870 
    [ 5.000,  7.500) = 3540 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     22.963 ms/op
     p(99.9990) =     25.256 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 06:19:59.469 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.472 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.521 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.523 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.543 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.543 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.592 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.592 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.593 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.597 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.597 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.605 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.606 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.608 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.611 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.611 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.779 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:19:59.817 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:19:59.832 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:19:59.928 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.961 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:19:59.961 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.224 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:20:00.241 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.242 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.242 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.243 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.276 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.432 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.124
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
06:20:00.432 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.124
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
06:20:00.689 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.691 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.710 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.725 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.731 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.817 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.866 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3653&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672554000807&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.867 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3653&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672554000807&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.955 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.975 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3653&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672554000807&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.977 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.124
06:20:00.982 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.124
6.468 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.215 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.662 ±(99.9%) 0.013 ms/op
Iteration   1: 4.700 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.585 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  14.445 ms/op
                 listUser·p0.9999: 16.190 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   2: 4.750 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   8.360 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 22.062 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 06:21:01.730 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.738 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.738 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.739 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.739 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.740 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.740 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:01.742 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.124:20881, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.748 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.124:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3653&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672554000807&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.748 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.749 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.750 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3653&protocol=grpc&register.ip=10.1.0.124&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.750 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.751 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.124&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3653&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1672554000807&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.751 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.751 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.751 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.752 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.753 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.753 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.753 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.753 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.755 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.755 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.755 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.755 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.755 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.124
06:21:03.757 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.124
4.661 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  19.634 ms/op
                 listUser·p0.9999: 28.812 ms/op
                 listUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204107
  mean =      4.703 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 442 
    [ 2.500,  5.000) = 157295 
    [ 5.000,  7.500) = 42027 
    [ 7.500, 10.000) = 3685 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.224 ms/op
     p(99.9000) =     16.136 ms/op
     p(99.9900) =     27.915 ms/op
     p(99.9990) =     30.108 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.872 ± 2.328  ops/ms
ClientGrpc.existUser                       thrpt       3   9.021 ± 3.167  ops/ms
ClientGrpc.getUser                         thrpt       3   8.779 ± 0.922  ops/ms
ClientGrpc.listUser                        thrpt       3   6.916 ± 1.339  ops/ms
ClientGrpc.createUser                       avgt       3   3.649 ± 0.863   ms/op
ClientGrpc.existUser                        avgt       3   3.501 ± 1.441   ms/op
ClientGrpc.getUser                          avgt       3   3.601 ± 1.240   ms/op
ClientGrpc.listUser                         avgt       3   4.578 ± 1.633   ms/op
ClientGrpc.createUser                     sample  260806   3.680 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.724           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.023           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.692           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.940           ms/op
ClientGrpc.existUser                      sample  276167   3.475 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.956           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.940           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.072           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.537           ms/op
ClientGrpc.getUser                        sample  262386   3.658 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.923           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.963           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.723           ms/op
ClientGrpc.listUser                       sample  204107   4.703 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.182           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.514           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.136           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.915           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.376           ms/op
```
