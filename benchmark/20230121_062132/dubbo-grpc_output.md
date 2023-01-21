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
[INFO] benchmark-base ..................................... SUCCESS [  3.351 s]
[INFO] server-base ........................................ SUCCESS [  0.467 s]
[INFO] client-base ........................................ SUCCESS [  0.753 s]
[INFO] dubbo-grpc-client .................................. SUCCESS [  0.612 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.505 s
[INFO] Finished at: 2023-01-21T06:07:48Z
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
# Warmup Iteration   1: 06:07:49.852 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.855 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.910 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.912 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.929 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.930 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.971 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.972 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.972 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.976 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.977 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.984 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.984 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.986 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.989 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:07:49.989 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.128 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:07:50.161 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:07:50.174 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:07:50.267 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.279 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.477 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:07:50.509 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.510 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.512 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.512 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.539 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.666 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:07:50.666 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:07:50.838 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.839 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.846 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.851 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.853 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.898 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.941 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2047&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281270882&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:50.941 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2047&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281270882&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:51.043 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:07:51.057 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2047&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281270882&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:07:51.058 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:07:51.071 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
4.254 ops/ms
# Warmup Iteration   2: 9.170 ops/ms
# Warmup Iteration   3: 10.123 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 06:08:51.201 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.208 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.208 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.208 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.209 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.212 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.214 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:51.215 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.229 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2047&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281270882&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.230 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.231 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2047&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2047&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281270882&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.233 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.234 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.234 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.235 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.235 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.236 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.236 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.236 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.236 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.236 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.237 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.237 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.237 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.237 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.237 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:53.252 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.92
10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.058 ±(99.9%) 1.720 ops/ms [Average]
  (min, avg, max) = (9.966, 10.058, 10.155), stdev = 0.094
  CI (99.9%): [8.339, 11.778] (assumes normal distribution)


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
# Warmup Iteration   1: 06:08:55.043 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.048 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.101 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.102 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.120 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.121 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.163 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.163 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.163 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.167 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.167 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.175 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.175 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.177 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.179 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.180 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b145a0f, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.327 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:08:55.374 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:08:55.398 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:08:55.495 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.520 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.521 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.747 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:08:55.762 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.763 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.763 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.764 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.781 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:55.905 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:08:55.905 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:08:56.112 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.114 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.139 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.145 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.194 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.235 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2363&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281336188&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.236 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2363&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281336188&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.324 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.339 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2363&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281336188&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.341 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:08:56.346 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
7.426 ops/ms
# Warmup Iteration   2: 10.099 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.712 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 06:09:56.461 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.465 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.465 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.465 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.465 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.468 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.468 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:56.469 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.477 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2363&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281336188&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.478 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.484 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.484 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2363&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.485 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.485 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2363&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281336188&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.485 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.485 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.485 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.486 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.486 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.487 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.487 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.487 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.487 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.487 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.487 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.488 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:09:58.499 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b145a0f, dubbo version: 3.1.0, current host: 10.1.0.92
10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.643 ±(99.9%) 1.980 ops/ms [Average]
  (min, avg, max) = (10.518, 10.643, 10.712), stdev = 0.109
  CI (99.9%): [8.662, 12.623] (assumes normal distribution)


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
# Warmup Iteration   1: 06:10:00.299 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.315 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.358 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.360 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.377 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.378 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.419 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.419 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.420 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.423 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.424 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.431 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.431 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.433 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.435 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.435 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.576 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:10:00.607 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:10:00.620 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:10:00.695 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.703 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.709 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.945 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:10:00.969 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.970 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.970 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:00.971 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.005 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.141 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:10:01.141 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:10:01.366 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.374 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.388 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.394 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.399 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.478 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.524 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2539&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281401468&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.525 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2539&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281401468&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.584 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.595 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2539&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281401468&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.596 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:10:01.602 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
6.736 ops/ms
# Warmup Iteration   2: 9.785 ops/ms
# Warmup Iteration   3: 9.965 ops/ms
Iteration   1: 10.154 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 06:11:01.708 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.713 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.713 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.714 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.714 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.721 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.722 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:01.726 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.734 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2539&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281401468&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.734 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.735 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.736 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2539&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.736 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.737 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2539&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281401468&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.737 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.737 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.737 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.739 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.739 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.740 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.740 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.740 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.740 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.740 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.741 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.742 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.742 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:03.743 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.92
10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.218 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (10.154, 10.218, 10.271), stdev = 0.059
  CI (99.9%): [9.141, 11.295] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 06:11:05.523 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.526 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.568 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.570 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.588 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.589 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.631 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.632 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.632 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.636 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.638 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.645 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.646 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.648 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.650 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.650 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.789 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:11:05.823 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:11:05.836 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:11:05.939 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.949 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:05.953 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.142 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:11:06.158 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.159 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.159 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.159 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.177 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.297 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:11:06.298 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:11:06.468 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.470 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.477 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.483 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.485 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.514 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.547 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2665&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281466507&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.548 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2665&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281466507&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.633 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.645 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2665&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281466507&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.646 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:11:06.654 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
5.842 ops/ms
# Warmup Iteration   2: 7.520 ops/ms
# Warmup Iteration   3: 7.857 ops/ms
Iteration   1: 7.905 ops/ms
Iteration   2: 7.675 ops/ms
Iteration   3: 06:12:06.764 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.769 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.772 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.772 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.773 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.774 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.774 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:06.775 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.785 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2665&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281466507&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.785 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.786 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.787 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2665&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.787 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.787 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2665&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281466507&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.787 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.787 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.788 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.789 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.789 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.790 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:08.801 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.92
7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.805 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (7.675, 7.805, 7.905), stdev = 0.118
  CI (99.9%): [5.659, 9.950] (assumes normal distribution)


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
# Warmup Iteration   1: 06:12:10.605 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.608 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.650 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.652 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.670 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.671 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.713 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.713 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.713 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.717 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.718 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.725 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.725 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.735 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.737 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.739 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:10.879 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:12:10.918 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:12:10.941 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:12:11.040 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.051 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.052 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.281 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:12:11.297 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.297 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.297 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.298 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.316 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.442 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:12:11.442 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:12:11.610 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.612 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.619 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.624 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.627 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.661 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.712 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2775&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281531654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.712 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2775&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281531654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.782 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.799 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2775&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281531654&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.800 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:12:11.806 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
4.348 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.002 ms/op
Iteration   1: 3.215 ±(99.9%) 0.002 ms/op
Iteration   2: 3.279 ±(99.9%) 0.001 ms/op
Iteration   3: 06:13:11.919 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.925 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.925 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.927 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.928 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.931 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.932 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:11.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.944 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2775&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281531654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.945 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.947 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2775&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2775&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281531654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.949 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.949 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.950 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:13.953 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.92
3.190 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.228 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (3.190, 3.228, 3.279), stdev = 0.046
  CI (99.9%): [2.388, 4.068] (assumes normal distribution)


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
# Warmup Iteration   1: 06:13:15.714 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.719 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.786 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.787 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.807 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.807 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.849 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.849 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.849 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.853 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.853 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.860 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.861 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.863 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.865 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:13:15.866 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.006 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:13:16.047 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:13:16.060 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:13:16.181 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.188 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.188 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.404 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:13:16.419 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.420 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.420 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.420 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.438 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.562 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:13:16.562 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:13:16.732 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.733 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.743 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.749 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.759 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.814 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.855 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2946&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281596797&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.856 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2946&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281596797&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.978 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.991 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2946&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281596797&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.992 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:13:16.997 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
4.029 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 2.972 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 06:14:17.102 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.108 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.108 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.109 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.110 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.111 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.112 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:17.113 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.123 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2946&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281596797&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.124 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.130 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2946&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2946&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281596797&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.131 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.132 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.132 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.133 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.133 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.133 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.133 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.133 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.133 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.134 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.134 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.138 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.138 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.138 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.138 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.138 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:19.139 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.92
2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.990 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (2.963, 2.990, 3.036), stdev = 0.040
  CI (99.9%): [2.269, 3.711] (assumes normal distribution)


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
# Warmup Iteration   1: 06:14:20.898 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:14:20.901 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:20.946 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:20.948 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:20.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:20.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.010 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.010 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.017 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.017 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.020 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.022 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.022 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.162 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:14:21.213 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:14:21.242 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:14:21.355 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.373 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.378 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.607 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:14:21.632 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.633 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.633 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.634 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.663 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:21.790 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:14:21.790 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:14:22.005 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.022 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.028 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.038 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.091 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.132 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3050&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281662077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.133 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3050&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281662077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.229 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.242 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3050&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281662077&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.243 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:14:22.249 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
4.406 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.003 ms/op
Iteration   1: 3.151 ±(99.9%) 0.003 ms/op
Iteration   2: 3.193 ±(99.9%) 0.003 ms/op
Iteration   3: 06:15:22.365 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.369 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.371 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.371 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.371 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.375 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.375 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:22.376 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.387 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3050&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281662077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.387 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.388 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3050&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3050&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281662077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.390 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.392 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.393 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.394 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.394 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.394 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.394 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:24.396 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.92
3.208 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.184 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.151, 3.184, 3.208), stdev = 0.030
  CI (99.9%): [2.644, 3.724] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 06:15:26.146 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.150 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.223 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.225 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.249 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.249 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.294 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.294 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.294 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.298 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.299 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.306 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.306 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.308 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.449 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:15:26.482 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:15:26.496 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:15:26.568 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.588 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.589 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.791 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:15:26.806 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.806 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.806 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.807 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.825 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:26.946 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:15:26.946 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:15:27.130 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.132 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.146 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.155 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.158 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.200 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.261 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3159&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281727187&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.261 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3159&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281727187&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.343 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.359 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3159&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281727187&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.360 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:15:27.365 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
5.639 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.046 ms/op
Iteration   1: 3.932 ±(99.9%) 0.012 ms/op
Iteration   2: 4.049 ±(99.9%) 0.019 ms/op
Iteration   3: 06:16:27.487 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.492 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.492 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.492 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.493 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.494 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.494 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:27.496 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.510 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3159&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281727187&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.510 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.513 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.514 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3159&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.514 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.515 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3159&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281727187&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.515 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.515 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.515 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.516 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.516 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.517 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.517 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.517 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.517 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.518 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.518 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.518 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.518 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.519 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.519 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.519 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.519 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.519 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:29.520 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-27] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.92
3.985 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.989 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.932, 3.989, 4.049), stdev = 0.058
  CI (99.9%): [2.927, 5.051] (assumes normal distribution)


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
# Warmup Iteration   1: 06:16:31.310 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.313 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.358 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.360 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.377 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.378 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.419 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.420 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.420 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.424 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.424 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.431 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.431 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.433 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.435 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.436 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.580 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:16:31.612 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:16:31.631 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:16:31.748 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.758 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.763 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:16:31.966 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.966 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.966 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.967 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:31.984 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.110 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:16:32.110 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:16:32.278 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.280 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.315 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.320 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.326 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.381 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3266&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281792370&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3266&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281792370&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.464 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.474 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3266&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281792370&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.475 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:16:32.480 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
4.259 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.037 ms/op
                 createUser·p0.9999: 22.466 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  10.554 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   3: 06:17:33.325 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.331 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.332 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.332 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.332 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.333 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.334 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:33.335 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.344 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3266&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281792370&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.345 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.349 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.350 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3266&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.350 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.350 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3266&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281792370&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.350 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.350 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.351 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.352 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.352 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.354 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.354 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.354 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.354 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.354 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.354 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.355 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.355 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:35.359 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.92
3.174 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  10.063 ms/op
                 createUser·p0.9999: 16.840 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303018
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25819 
    [ 2.500,  5.000) = 275396 
    [ 5.000,  7.500) = 1413 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     21.771 ms/op
     p(99.9990) =     22.642 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 06:17:37.265 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.267 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.309 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.310 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.328 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.329 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.370 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.371 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.371 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.375 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.375 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.382 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.382 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.384 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.386 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.387 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@33b0b6f9, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.525 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:17:37.560 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:17:37.573 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:17:37.659 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.681 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.682 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.902 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:17:37.918 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.918 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.918 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.919 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:37.939 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.062 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:17:38.062 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:17:38.290 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.292 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.305 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.312 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.319 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.378 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.443 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3375&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281858364&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.444 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3375&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281858364&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.512 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.528 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3375&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281858364&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.529 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:17:38.534 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
3.925 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  7.817 ms/op
                 existUser·p0.9999: 14.095 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.594 ms/op
                 existUser·p0.9999: 14.228 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   3: 06:18:38.976 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.980 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.981 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.981 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.981 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.982 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.982 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:38.983 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.994 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3375&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281858364&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.994 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.995 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.996 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3375&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.996 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.996 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3375&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281858364&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.997 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.997 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.997 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:40.998 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.001 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.002 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.002 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.002 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.002 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.002 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.002 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.003 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.003 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.003 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.003 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.004 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.004 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.004 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:41.008 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@33b0b6f9, dubbo version: 3.1.0, current host: 10.1.0.92
3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.258 ms/op
                 existUser·p0.9999: 16.499 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320608
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2792 
    [ 1.250,  2.500) = 39119 
    [ 2.500,  3.750) = 255656 
    [ 3.750,  5.000) = 22041 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.266 ms/op
     p(99.9900) =     14.827 ms/op
     p(99.9990) =     16.869 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 06:18:42.820 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.823 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.886 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.887 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.916 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.916 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.969 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.970 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.976 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.977 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.979 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.981 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:18:42.981 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@33b0b6f9, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.120 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:18:43.153 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:18:43.166 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:18:43.271 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.282 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.283 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.493 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:18:43.508 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.509 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.509 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.510 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.531 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.658 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:18:43.658 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:18:43.824 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.833 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.838 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.840 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.868 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.888 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3479&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281923862&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.888 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3479&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281923862&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:43.987 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:18:44.000 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3479&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281923862&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:18:44.001 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:18:44.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
4.095 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.107 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.945 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.386 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  10.660 ms/op
                 getUser·p0.9999: 21.809 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 06:19:44.751 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.756 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.756 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.756 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.756 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.758 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.762 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:44.765 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.772 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3479&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281923862&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.772 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.775 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3479&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.776 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.776 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3479&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281923862&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.776 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.776 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.776 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.777 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.778 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.778 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.778 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.779 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:46.784 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@33b0b6f9, dubbo version: 3.1.0, current host: 10.1.0.92
3.075 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.504 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301478
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22795 
    [ 2.500,  5.000) = 271636 
    [ 5.000,  7.500) = 4662 
    [ 7.500, 10.000) = 2132 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     23.228 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 06:19:48.605 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.608 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.649 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.650 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.667 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.668 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.709 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.709 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.709 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.713 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.713 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.720 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.720 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.722 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.724 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.724 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:48.862 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
06:19:48.895 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
06:19:48.907 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
06:19:48.993 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.005 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.006 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.228 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
06:19:49.246 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.247 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.247 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.247 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.266 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.405 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.92
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
06:19:49.405 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.92
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
06:19:49.580 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.581 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.588 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.593 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.596 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.625 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.644 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3585&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281989618&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.644 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3585&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281989618&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.699 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.711 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3585&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281989618&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.712 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.92
06:19:49.718 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.92
5.552 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.011 ms/op
Iteration   1: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.996 ms/op
                 listUser·p0.9999: 20.022 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.658 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 06:20:50.289 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.293 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.293 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.293 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.293 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.295 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.295 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:50.296 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.92:20881, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.307 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.92:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3585&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281989618&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.308 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.309 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3585&protocol=grpc&register.ip=10.1.0.92&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.92&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3585&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1674281989618&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.312 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.313 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.313 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.313 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.92
06:20:52.317 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-16] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.92
4.046 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.471 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 19.631 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238259
  mean =      4.029 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3826 
    [ 2.500,  5.000) = 204544 
    [ 5.000,  7.500) = 28116 
    [ 7.500, 10.000) = 1210 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.593 ms/op
     p(99.9900) =     19.678 ms/op
     p(99.9990) =     20.271 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.058 ± 1.720  ops/ms
ClientGrpc.existUser                       thrpt       3  10.643 ± 1.980  ops/ms
ClientGrpc.getUser                         thrpt       3  10.218 ± 1.077  ops/ms
ClientGrpc.listUser                        thrpt       3   7.805 ± 2.145  ops/ms
ClientGrpc.createUser                       avgt       3   3.228 ± 0.840   ms/op
ClientGrpc.existUser                        avgt       3   2.990 ± 0.721   ms/op
ClientGrpc.getUser                          avgt       3   3.184 ± 0.540   ms/op
ClientGrpc.listUser                         avgt       3   3.989 ± 1.062   ms/op
ClientGrpc.createUser                     sample  303018   3.168 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.795           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.771           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  320608   2.993 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.827           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.039           ms/op
ClientGrpc.getUser                        sample  301478   3.183 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.719           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.283           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.470           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.228           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.790           ms/op
ClientGrpc.listUser                       sample  238259   4.029 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.471           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.593           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.678           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.349           ms/op
```
