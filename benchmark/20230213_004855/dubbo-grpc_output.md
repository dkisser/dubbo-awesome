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
[INFO] benchmark-base ..................................... SUCCESS [  3.431 s]
[INFO] server-base ........................................ SUCCESS [  0.472 s]
[INFO] client-base ........................................ SUCCESS [  0.763 s]
[INFO] dubbo-grpc-client .................................. SUCCESS [  0.540 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.628 s
[INFO] Finished at: 2023-02-13T00:34:59Z
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
# Warmup Iteration   1: 00:35:00.708 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.719 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.767 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.769 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.787 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.787 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.829 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.830 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.830 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.835 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.835 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.842 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.842 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.844 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.847 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.847 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:00.986 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:35:01.019 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:35:01.033 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:35:01.146 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.174 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.174 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.385 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:35:01.414 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.415 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.445 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.575 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:35:01.575 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:35:01.776 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.779 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.786 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.795 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.800 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.868 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.887 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2049&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248501861&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.888 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2049&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248501861&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.927 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.938 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2049&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248501861&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.938 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:35:01.943 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
4.061 ops/ms
# Warmup Iteration   2: 8.976 ops/ms
# Warmup Iteration   3: 9.985 ops/ms
Iteration   1: 10.180 ops/ms
Iteration   2: 9.876 ops/ms
Iteration   3: 00:36:02.057 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.068 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.069 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.069 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.069 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.070 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.071 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:02.074 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.080 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2049&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248501861&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.081 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2049&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.082 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.083 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2049&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248501861&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.083 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.083 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.083 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.084 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.084 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.085 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.086 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:04.092 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.47
10.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.068 ±(99.9%) 3.040 ops/ms [Average]
  (min, avg, max) = (9.876, 10.068, 10.180), stdev = 0.167
  CI (99.9%): [7.027, 13.108] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 00:36:05.920 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:36:05.925 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:05.978 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:05.980 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:05.997 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:05.998 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.040 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.040 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.040 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.044 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.045 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.051 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.052 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.054 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.056 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.056 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.194 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:36:06.226 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:36:06.239 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:36:06.318 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.350 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.351 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.572 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:36:06.592 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.592 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.592 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.593 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.655 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:06.827 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:36:06.827 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:36:07.086 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.088 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.104 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.112 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.117 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.177 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.225 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2440&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248567164&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.227 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2440&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248567164&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.303 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.314 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2440&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248567164&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.315 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:36:07.320 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
7.002 ops/ms
# Warmup Iteration   2: 10.048 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 00:37:07.408 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.415 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.415 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.415 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.415 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.417 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.418 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:07.419 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.428 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2440&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248567164&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.428 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.429 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2440&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2440&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248567164&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.430 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.431 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.432 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.433 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.433 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.433 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.434 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.434 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.434 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.434 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.434 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.435 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.435 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.435 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.435 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.435 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:09.441 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.47
10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.552 ±(99.9%) 3.215 ops/ms [Average]
  (min, avg, max) = (10.348, 10.552, 10.663), stdev = 0.176
  CI (99.9%): [7.337, 13.766] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 00:37:11.249 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.252 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.316 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.318 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.336 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.337 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.382 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.383 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.383 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.389 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.389 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.396 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.396 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.398 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.401 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.401 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.540 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:37:11.572 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:37:11.585 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:37:11.653 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.677 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.678 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.848 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:37:11.867 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.867 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.867 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.868 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:11.886 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:37:12.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:37:12.174 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.175 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.182 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.188 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.190 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.242 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.308 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2571&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248632230&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.308 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2571&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248632230&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.404 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2571&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248632230&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.405 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:37:12.411 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
6.895 ops/ms
# Warmup Iteration   2: 9.975 ops/ms
# Warmup Iteration   3: 10.080 ops/ms
Iteration   1: 9.883 ops/ms
Iteration   2: 10.037 ops/ms
Iteration   3: 00:38:12.533 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.537 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.538 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.541 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.541 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.542 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.542 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:12.544 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.552 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2571&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248632230&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.552 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.553 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2571&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2571&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248632230&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.555 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.555 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.556 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.556 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.558 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.558 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.558 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.558 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.558 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:14.563 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-31] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.006 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (9.883, 10.006, 10.098), stdev = 0.111
  CI (99.9%): [7.979, 12.033] (assumes normal distribution)


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
# Warmup Iteration   1: 00:38:16.343 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.388 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.390 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.407 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.408 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.449 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.450 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.450 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.454 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.454 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.461 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.461 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.464 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.467 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.467 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@27bb94d1, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.605 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:38:16.645 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:38:16.658 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:38:16.750 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.764 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.767 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.940 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:38:16.958 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.959 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.959 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.960 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:16.977 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.114 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:38:17.115 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:38:17.279 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.281 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.288 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.294 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.296 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.325 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.343 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2682&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248697318&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.344 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2682&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248697318&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.456 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.473 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2682&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248697318&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.474 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:38:17.480 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
5.698 ops/ms
# Warmup Iteration   2: 7.609 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 7.799 ops/ms
Iteration   3: 00:39:17.612 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.616 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.621 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.621 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.621 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.623 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.624 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:17.625 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.633 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2682&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248697318&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.633 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.634 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.635 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2682&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.635 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.635 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2682&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248697318&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.635 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.635 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.636 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.637 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.637 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.638 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.638 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.638 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.638 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.639 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.639 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.639 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.639 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.640 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.640 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.640 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.640 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.640 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:19.642 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@27bb94d1, dubbo version: 3.1.0, current host: 10.1.0.47
7.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.840 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (7.799, 7.840, 7.875), stdev = 0.038
  CI (99.9%): [7.145, 8.534] (assumes normal distribution)


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
# Warmup Iteration   1: 00:39:21.380 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.383 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.457 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.459 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.483 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.483 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.540 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.540 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.540 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.544 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.544 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.551 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.552 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.554 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.556 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.557 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.695 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:39:21.729 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:39:21.754 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:39:21.841 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.849 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:21.849 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.093 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:39:22.108 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.109 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.109 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.109 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.130 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.269 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:39:22.269 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:39:22.431 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.432 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.439 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.444 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.446 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.496 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.543 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2851&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248762485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.543 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2851&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248762485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.632 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.646 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2851&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248762485&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.647 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:39:22.659 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
4.431 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.004 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 00:40:22.766 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.769 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.770 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.770 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.770 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.779 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.779 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:22.782 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.790 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2851&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248762485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.791 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.793 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.794 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2851&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.794 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.794 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2851&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248762485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.794 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.794 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.794 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.795 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.796 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.796 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.797 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.798 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.798 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.798 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.798 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.798 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:24.800 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.47
3.133 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.152 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (3.133, 3.152, 3.187), stdev = 0.031
  CI (99.9%): [2.593, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 00:40:26.557 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.560 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.601 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.603 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.620 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.621 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.662 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.662 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.662 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.666 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.666 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.674 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.674 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.676 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.678 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.678 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.814 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:40:26.845 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:40:26.858 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:40:26.947 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.959 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:26.965 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.152 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:40:27.168 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.168 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.168 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.169 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.187 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.311 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:40:27.311 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:40:27.521 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.523 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.539 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.545 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.553 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.612 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.634 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2962&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248827597&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.635 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2962&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248827597&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.728 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.743 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2962&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248827597&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.744 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:40:27.749 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
3.921 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.002 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 2.957 ±(99.9%) 0.002 ms/op
Iteration   3: 00:41:27.870 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.875 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.876 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.876 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.876 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.879 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.879 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:27.892 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.904 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2962&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248827597&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.905 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.906 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.907 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2962&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.907 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.907 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2962&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248827597&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.907 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.907 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.907 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.908 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.915 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.916 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.916 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.916 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.916 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.917 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.917 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.917 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.917 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.917 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.917 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.918 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.918 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.918 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:29.920 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.47
3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.018 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (2.957, 3.018, 3.097), stdev = 0.072
  CI (99.9%): [1.704, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 00:41:31.659 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.662 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.726 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.728 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.746 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.746 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.806 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.806 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.807 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.815 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.815 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.822 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.822 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.824 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.826 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:31.967 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:41:31.999 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:41:32.012 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:41:32.110 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.135 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.135 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.328 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:41:32.351 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.355 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.356 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.356 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.385 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.515 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:41:32.515 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:41:32.687 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.688 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.695 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.700 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.702 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.730 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.775 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248892724&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.775 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248892724&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.852 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.865 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248892724&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.866 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:41:32.875 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
4.320 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.003 ms/op
Iteration   1: 3.134 ±(99.9%) 0.003 ms/op
Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
Iteration   3: 00:42:32.969 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.978 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.979 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.979 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.980 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.981 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.983 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:32.986 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:34.998 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248892724&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:34.999 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.001 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.002 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3073&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.002 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.003 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248892724&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.003 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.003 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.003 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.004 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.004 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.005 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.005 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.005 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.005 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.006 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.007 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:35.012 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
3.175 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.120, 3.143, 3.175), stdev = 0.028
  CI (99.9%): [2.629, 3.657] (assumes normal distribution)


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
# Warmup Iteration   1: 00:42:36.801 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.804 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.849 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.851 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.876 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.876 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.921 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.921 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.921 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.925 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.925 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.932 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.932 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.934 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.938 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:42:36.938 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.071 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:42:37.104 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:42:37.116 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:42:37.208 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.220 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.220 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.418 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:42:37.434 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.434 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.435 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.435 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.464 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.592 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:42:37.592 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:42:37.792 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.793 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.808 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.815 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.820 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.879 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.920 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3182&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248957866&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:37.921 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3182&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248957866&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:38.016 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:42:38.028 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3182&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248957866&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:42:38.030 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:42:38.043 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
5.554 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.023 ms/op
Iteration   1: 3.962 ±(99.9%) 0.020 ms/op
Iteration   2: 3.966 ±(99.9%) 0.005 ms/op
Iteration   3: 00:43:38.162 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.168 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.168 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.169 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.169 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.170 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.171 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:38.172 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.183 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3182&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248957866&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.183 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.184 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.185 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3182&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.185 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.186 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3182&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676248957866&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.186 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.186 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.186 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.187 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.187 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.188 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.189 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.189 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.189 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.189 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.190 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:40.195 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
4.062 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.996 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.962, 3.996, 4.062), stdev = 0.057
  CI (99.9%): [2.965, 5.028] (assumes normal distribution)


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
# Warmup Iteration   1: 00:43:41.956 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:43:41.959 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:41.999 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.000 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.017 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.018 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.060 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.060 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.061 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.064 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.065 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.072 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.072 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.074 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.076 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.077 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.217 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:43:42.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:43:42.290 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:43:42.374 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.401 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.402 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.625 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:43:42.640 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.641 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.641 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.641 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.659 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.779 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:43:42.779 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:43:42.942 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.943 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.950 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.955 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.957 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:42.988 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:43.033 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3289&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249022980&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:43.033 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3289&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249022980&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:43.132 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:43:43.150 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3289&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249022980&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:43:43.151 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:43:43.159 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
4.072 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.006 ms/op
Iteration   1: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.452 ms/op
                 createUser·p0.999:  8.203 ms/op
                 createUser·p0.9999: 13.353 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 3.220 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.597 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 00:44:43.716 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.721 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.721 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.721 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.721 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.723 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.724 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:43.725 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.740 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3289&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249022980&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.740 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.745 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3289&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.746 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3289&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249022980&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.747 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.748 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.749 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.750 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.750 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.750 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.750 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.751 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.751 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.751 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.751 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:45.757 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-28] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.47
3.187 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.307 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  13.417 ms/op
                 createUser·p0.9999: 17.104 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299822
  mean =      3.200 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21400 
    [ 2.500,  5.000) = 277266 
    [ 5.000,  7.500) = 773 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.267 ms/op
     p(99.9900) =     20.973 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 00:44:47.567 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.572 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.625 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.626 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.649 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.650 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.701 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.701 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.702 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.706 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.706 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.713 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.713 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.715 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.718 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.718 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:47.862 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:44:47.894 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:44:47.908 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:44:48.010 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.025 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.026 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.211 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:44:48.227 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.227 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.227 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.228 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.245 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.367 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:44:48.367 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:44:48.533 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.534 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.541 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.546 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.549 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.578 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.598 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3397&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249088571&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.598 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3397&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249088571&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.655 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.667 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3397&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249088571&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.667 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:44:48.672 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
3.799 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.593 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.341 ms/op
                 existUser·p0.9999: 22.491 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 00:45:49.334 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.341 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.342 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.342 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.342 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.344 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.344 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:49.345 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.356 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3397&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249088571&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.357 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.357 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.358 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3397&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.358 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.359 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3397&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249088571&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.359 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.359 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.359 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.360 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.360 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.361 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.361 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.361 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.361 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.362 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.362 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.362 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.362 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.362 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.362 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.363 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.363 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.363 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:51.375 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.47
3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.814 ms/op
                 existUser·p0.9999: 15.473 ms/op
                 existUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318743
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42042 
    [ 2.500,  5.000) = 275631 
    [ 5.000,  7.500) = 833 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.955 ms/op
     p(99.9900) =     20.890 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 00:45:53.189 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.192 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.235 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.237 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.254 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.254 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.295 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.295 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.296 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.299 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.300 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.307 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.307 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.309 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.312 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.312 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.449 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:45:53.482 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:45:53.494 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:45:53.571 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.599 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.600 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:45:53.796 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.796 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.796 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.797 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.813 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:53.935 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:45:53.935 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:45:54.104 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.105 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.112 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.117 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.120 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.160 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.199 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3500&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249154145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.200 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3500&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249154145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.300 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.317 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3500&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249154145&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.318 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:45:54.327 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
3.919 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.501 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.874 ms/op
                 getUser·p0.9999: 33.817 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   3: 00:46:54.740 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.747 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.747 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.747 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.747 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.749 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.751 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:54.752 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.767 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3500&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249154145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.767 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.769 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.769 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3500&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.770 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.770 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3500&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249154145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.770 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.770 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.770 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.771 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.772 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.772 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.772 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.773 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.774 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.774 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.774 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.774 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.774 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:56.776 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.47
3.175 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.827 ms/op
                 getUser·p0.9999: 20.705 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306090
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26647 
    [ 2.500,  5.000) = 278420 
    [ 5.000,  7.500) = 805 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =     32.355 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 00:46:58.576 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.593 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.642 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.643 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.661 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.662 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.710 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.711 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.711 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.715 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.715 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.722 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.722 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.724 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.726 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.727 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b145a0f, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:58.904 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:46:58.935 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:46:58.954 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:46:59.037 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.054 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.054 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:46:59.346 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.347 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.347 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.348 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.371 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.491 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.47
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
00:46:59.491 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.47
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
00:46:59.657 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.658 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.665 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.670 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.673 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.701 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.745 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3611&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249219695&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.746 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3611&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249219695&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.819 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.836 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3611&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249219695&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.838 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.47
00:46:59.843 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.47
5.308 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.012 ms/op
Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.766 ms/op
                 listUser·p0.9999: 19.593 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   6.999 ms/op
                 listUser·p0.999:  13.983 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 00:48:00.284 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.293 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.294 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.294 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.296 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.299 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.299 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:00.300 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.47:20881, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.309 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.47:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3611&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249219695&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.309 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.310 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3611&protocol=grpc&register.ip=10.1.0.47&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.47&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3611&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1676249219695&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.311 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.312 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.313 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.313 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.314 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.315 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.316 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.47
00:48:02.320 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-32] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b145a0f, dubbo version: 3.1.0, current host: 10.1.0.47
4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.458 ms/op
                 listUser·p0.9999: 23.560 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237946
  mean =      4.033 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2383 
    [ 2.500,  5.000) = 208953 
    [ 5.000,  7.500) = 25302 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.091 ms/op
     p(99.9900) =     21.640 ms/op
     p(99.9990) =     23.851 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.068 ± 3.040  ops/ms
ClientGrpc.existUser                       thrpt       3  10.552 ± 3.215  ops/ms
ClientGrpc.getUser                         thrpt       3  10.006 ± 2.027  ops/ms
ClientGrpc.listUser                        thrpt       3   7.840 ± 0.695  ops/ms
ClientGrpc.createUser                       avgt       3   3.152 ± 0.558   ms/op
ClientGrpc.existUser                        avgt       3   3.018 ± 1.314   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 0.514   ms/op
ClientGrpc.listUser                         avgt       3   3.996 ± 1.031   ms/op
ClientGrpc.createUser                     sample  299822   3.200 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.307           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.267           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  318743   3.014 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.755           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.955           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.396           ms/op
ClientGrpc.getUser                        sample  306090   3.136 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.570           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.685           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.355           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.817           ms/op
ClientGrpc.listUser                       sample  237946   4.033 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.790           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.091           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.640           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
```
