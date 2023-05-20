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
[INFO]   from pom.xml
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
[INFO] --- build-helper-maven-plugin:3.4.0:add-source (default) @ benchmark-base ---
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
[INFO]   from ../server-base/pom.xml
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
[INFO]   from ../client-base/pom.xml
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
[INFO]   from ../dubbo-grpc-client/pom.xml
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
[INFO] Copying grpc-netty-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-netty-1.47.0.jar
[INFO] Copying grpc-core-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-core-1.47.0.jar
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
[INFO] Copying perfmark-api-0.25.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/perfmark-api-0.25.0.jar
[INFO] Copying netty-transport-native-unix-common-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/netty-transport-native-unix-common-4.1.72.Final.jar
[INFO] Copying grpc-netty-shaded-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-netty-shaded-1.47.0.jar
[INFO] Copying grpc-protobuf-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-protobuf-1.47.0.jar
[INFO] Copying grpc-api-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-api-1.47.0.jar
[INFO] Copying grpc-context-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-context-1.47.0.jar
[INFO] Copying jsr305-3.0.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jsr305-3.0.2.jar
[INFO] Copying proto-google-common-protos-2.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/proto-google-common-protos-2.0.1.jar
[INFO] Copying grpc-protobuf-lite-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-protobuf-lite-1.47.0.jar
[INFO] Copying grpc-stub-1.47.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/grpc-stub-1.47.0.jar
[INFO] Copying jmh-core-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jmh-core-1.21.jar
[INFO] Copying jopt-simple-4.6.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jopt-simple-4.6.jar
[INFO] Copying commons-math3-3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/commons-math3-3.2.jar
[INFO] Copying jmh-generator-annprocess-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/jmh-generator-annprocess-1.21.jar
[INFO] Copying dubbo-3.1.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/dubbo-3.1.1.jar
[INFO] Copying spring-context-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-context-5.2.20.RELEASE.jar
[INFO] Copying spring-aop-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-aop-5.2.20.RELEASE.jar
[INFO] Copying spring-beans-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-beans-5.2.20.RELEASE.jar
[INFO] Copying spring-core-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-core-5.2.20.RELEASE.jar
[INFO] Copying spring-jcl-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-jcl-5.2.20.RELEASE.jar
[INFO] Copying spring-expression-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-expression-5.2.20.RELEASE.jar
[INFO] Copying spring-context-support-1.0.8.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/spring-context-support-1.0.8.jar
[INFO] Copying javassist-3.28.0-GA.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/javassist-3.28.0-GA.jar
[INFO] Copying snakeyaml-1.31.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/snakeyaml-1.31.jar
[INFO] Copying fastjson-1.2.83.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/fastjson-1.2.83.jar
[INFO] Copying fastjson2-2.0.14.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-grpc-client/target/libs/fastjson2-2.0.14.jar
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
[INFO] benchmark-base ..................................... SUCCESS [  4.608 s]
[INFO] server-base ........................................ SUCCESS [  0.613 s]
[INFO] client-base ........................................ SUCCESS [  0.871 s]
[INFO] dubbo-grpc-client .................................. SUCCESS [  0.596 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  7.105 s
[INFO] Finished at: 2023-05-20T00:28:47Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-grpc-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-grpc-client/target/dubbo-grpc-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 00:28:49.060 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.064 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.134 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.137 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.166 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.166 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.226 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.228 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.232 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.243 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.244 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.256 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.256 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.259 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.263 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.264 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.454 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:28:49.499 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:28:49.517 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:28:49.659 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.670 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.671 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.960 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:28:49.994 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.997 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:49.998 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.000 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.035 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.209 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:28:50.210 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:28:50.490 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.492 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.514 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.523 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.529 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.632 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:28:50.662 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2059&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542530615&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.663 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2059&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542530615&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.754 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.793 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2059&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542530615&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.795 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:50.805 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
00:28:51.696 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-10] WARN  o.a.d.r.p.InvokerInvocationHandler -  [DUBBO] [Dubbo-Consumer] execute service org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService#createUser cost 828.820756 ms, this invocation almost (maybe already) timeout. Timeout: 1000ms
invocation context:
remote.application=dubbo-grpc-client;
thread info: 
Start time: 248852058428
+-[ Offset: 0.000000ms; Usage: 828.820756ms, 100% ] Receive request. Client invoke begin. ServiceKey: org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService MethodName:createUser
  +-[ Offset: 10.662515ms; Usage: 818.114039ms, 98% ] Invoker invoke. Target Address: localhost:8080
     +-[ Offset: 19.798271ms; Usage: 808.920681ms, 97% ] Receive request. Server biz impl invoke begin., dubbo version: 3.1.1, current host: 10.1.0.164
2.289 ops/ms
# Warmup Iteration   2: 5.162 ops/ms
# Warmup Iteration   3: 6.446 ops/ms
Iteration   1: 6.758 ops/ms
Iteration   2: 7.418 ops/ms
Iteration   3: 00:29:50.962 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:50.968 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:50.968 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:50.969 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:50.969 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:29:50.973 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:50.974 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.990 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2059&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542530615&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.991 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.994 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.998 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2059&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.998 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.998 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2059&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542530615&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.998 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.998 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:52.999 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.000 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.001 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.002 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.002 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.003 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.003 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.003 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.003 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.005 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.005 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.006 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.006 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.007 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.008 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.010 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:53.012 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-11] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
7.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.103 ±(99.9%) 6.037 ops/ms [Average]
  (min, avg, max) = (6.758, 7.103, 7.418), stdev = 0.331
  CI (99.9%): [1.066, 13.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 00:29:55.032 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.036 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.094 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.096 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.118 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.118 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.174 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.174 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.175 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.185 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.185 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.196 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.196 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.199 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.202 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.203 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.392 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:29:55.456 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:29:55.472 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:29:55.582 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.600 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.604 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.909 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:29:55.944 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.945 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.945 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.946 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:55.976 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.174 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:29:56.174 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:29:56.395 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.396 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.406 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.413 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.416 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.477 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:29:56.526 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2371&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542596457&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.527 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2371&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542596457&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.640 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.669 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2371&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542596457&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.670 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:29:56.676 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
4.555 ops/ms
# Warmup Iteration   2: 6.887 ops/ms
# Warmup Iteration   3: 7.436 ops/ms
Iteration   1: 7.622 ops/ms
Iteration   2: 7.747 ops/ms
Iteration   3: 00:30:56.812 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:56.817 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:56.818 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:56.819 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:56.820 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:30:56.821 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:56.825 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.839 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2371&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542596457&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.839 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.840 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.841 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2371&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.842 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.842 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2371&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542596457&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.842 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.842 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.843 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.844 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.845 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.846 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.847 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.847 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.848 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.848 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.848 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:30:58.852 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
7.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.671 ±(99.9%) 1.209 ops/ms [Average]
  (min, avg, max) = (7.622, 7.671, 7.747), stdev = 0.066
  CI (99.9%): [6.463, 8.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 00:31:00.865 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:31:00.872 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:00.960 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:00.962 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.000 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.000 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.062 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.062 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.062 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.068 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.068 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.079 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.080 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.083 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.086 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.087 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.305 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:31:01.361 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:31:01.385 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:31:01.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.568 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.571 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.848 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:31:01.891 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.893 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.893 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.894 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:01.931 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.106 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:31:02.107 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:31:02.364 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.374 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.391 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.400 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.409 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.477 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:31:02.557 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2485&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542662460&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.558 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2485&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542662460&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.627 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.657 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2485&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542662460&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.659 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:31:02.665 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
4.017 ops/ms
# Warmup Iteration   2: 6.703 ops/ms
# Warmup Iteration   3: 7.067 ops/ms
Iteration   1: 7.137 ops/ms
Iteration   2: 7.214 ops/ms
Iteration   3: 00:32:02.803 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:02.809 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:02.809 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:02.809 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:02.810 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:32:02.811 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:02.811 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.821 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2485&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542662460&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.822 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.825 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2485&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2485&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542662460&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.827 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.828 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.829 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.830 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.831 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.831 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.831 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.832 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.832 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.832 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.833 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.833 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.834 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.835 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:04.845 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
7.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.138 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (7.062, 7.138, 7.214), stdev = 0.076
  CI (99.9%): [5.746, 8.529] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 00:32:06.824 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.828 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.889 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.916 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.917 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.976 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.977 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.977 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.984 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.984 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.996 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:32:06.997 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.001 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.006 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.006 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.186 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:32:07.230 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:32:07.259 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:32:07.439 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.449 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.449 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.699 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:32:07.720 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.720 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.721 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.721 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:07.910 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:32:07.911 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:32:08.162 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.165 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.184 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.197 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.204 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.296 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:32:08.344 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2591&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542728276&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.345 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2591&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542728276&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.503 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.538 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2591&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542728276&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.539 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:32:08.547 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
3.599 ops/ms
# Warmup Iteration   2: 5.152 ops/ms
# Warmup Iteration   3: 5.465 ops/ms
Iteration   1: 5.671 ops/ms
Iteration   2: 5.457 ops/ms
Iteration   3: 00:33:08.704 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:08.711 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:08.712 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:08.712 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:08.713 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:33:08.714 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:08.715 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.727 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2591&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542728276&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.727 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.730 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.731 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2591&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.731 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.731 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2591&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542728276&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.731 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.732 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.732 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.733 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.734 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.741 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.742 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.745 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.746 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.747 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.748 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.749 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.749 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.750 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.751 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.751 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.752 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.752 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:10.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
5.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.549 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (5.457, 5.549, 5.671), stdev = 0.110
  CI (99.9%): [3.537, 7.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 00:33:12.776 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.780 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.845 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.847 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.874 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.875 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.933 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.934 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.934 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.940 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.940 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.953 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.956 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.959 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:33:12.960 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.160 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:33:13.210 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:33:13.228 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:33:13.377 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.386 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.387 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.714 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:33:13.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.752 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.753 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.754 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.793 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:13.983 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:33:13.983 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:33:14.212 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.214 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.225 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.240 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.244 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.326 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:33:14.379 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2687&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542794307&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.380 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2687&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542794307&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.469 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.500 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2687&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542794307&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.501 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:33:14.509 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
6.900 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.724 ±(99.9%) 0.010 ms/op
Iteration   1: 4.652 ±(99.9%) 0.004 ms/op
Iteration   2: 4.537 ±(99.9%) 0.003 ms/op
Iteration   3: 00:34:14.648 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:14.652 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:14.653 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:14.653 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:14.654 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:34:14.656 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:14.657 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.666 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2687&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542794307&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.667 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.670 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.672 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2687&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.672 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.672 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2687&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542794307&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.672 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.672 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.673 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.674 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.675 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.675 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.675 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.676 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.677 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.677 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.678 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.678 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.678 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:16.687 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
4.507 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.565 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (4.507, 4.565, 4.652), stdev = 0.077
  CI (99.9%): [3.162, 5.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 00:34:18.778 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.782 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.842 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.844 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.872 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.873 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.939 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.940 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.940 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.946 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.947 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.957 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.958 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.961 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.965 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:34:18.965 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.195 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:34:19.238 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:34:19.265 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:34:19.408 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.428 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.429 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.690 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:34:19.714 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.714 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.714 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.715 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.738 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:19.894 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:34:19.895 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:34:20.103 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.105 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.113 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.120 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.123 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.166 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:34:20.191 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2782&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542860155&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.192 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2782&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542860155&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.266 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.298 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2782&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542860155&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.299 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:34:20.309 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
5.983 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.003 ms/op
Iteration   1: 4.280 ±(99.9%) 0.003 ms/op
Iteration   2: 4.250 ±(99.9%) 0.004 ms/op
Iteration   3: 00:35:20.454 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:20.459 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:20.459 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:20.459 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:20.460 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:35:20.461 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:20.464 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.478 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2782&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542860155&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.479 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.481 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.482 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2782&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.483 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.483 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2782&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542860155&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.483 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.483 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.484 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.490 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.490 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.491 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.492 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.493 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.493 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.493 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.493 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.493 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.494 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.494 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.494 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.494 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.495 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.495 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:22.504 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-24] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
4.223 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.251 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (4.223, 4.251, 4.280), stdev = 0.029
  CI (99.9%): [3.729, 4.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 00:35:24.494 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.498 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.554 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.556 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.580 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.581 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.635 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.636 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.636 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.641 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.641 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.651 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.651 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.654 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.657 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.657 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4ff269cc, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:24.874 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:35:24.929 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:35:24.958 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:35:25.130 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.145 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.146 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.395 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:35:25.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.417 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.418 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.444 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.605 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:35:25.606 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:35:25.804 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.806 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.815 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.821 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.824 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.918 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:35:25.965 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542925907&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:25.966 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542925907&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:26.058 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:35:26.099 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542925907&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:35:26.101 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:35:26.109 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
6.807 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.604 ±(99.9%) 0.006 ms/op
Iteration   1: 4.438 ±(99.9%) 0.003 ms/op
Iteration   2: 4.596 ±(99.9%) 0.004 ms/op
Iteration   3: 00:36:26.251 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:26.256 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:26.256 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:26.257 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:26.258 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:36:26.259 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:26.260 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.274 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542925907&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.275 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.276 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.277 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2888&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.277 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.278 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542925907&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.278 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.278 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.279 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.280 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.281 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.282 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.282 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.283 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.283 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.283 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.283 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.283 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.284 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.284 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.284 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.285 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.285 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.285 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:28.293 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4ff269cc, dubbo version: 3.1.1, current host: 10.1.0.164
4.526 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.520 ±(99.9%) 1.449 ms/op [Average]
  (min, avg, max) = (4.438, 4.520, 4.596), stdev = 0.079
  CI (99.9%): [3.071, 5.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 00:36:30.285 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.292 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.375 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.377 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.402 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.403 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.464 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.465 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.465 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.471 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.472 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.483 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.483 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.487 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.491 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.491 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4ff269cc, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.721 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:36:30.782 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:36:30.813 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:36:30.964 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.976 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:30.977 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.273 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:36:31.291 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.292 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.292 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.292 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.324 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.502 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:36:31.502 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:36:31.752 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.754 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.773 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.781 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.786 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.891 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:36:31.955 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2983&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542991844&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:31.959 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2983&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542991844&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:32.020 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:36:32.056 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2983&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542991844&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:36:32.057 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:36:32.064 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
8.186 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.257 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.671 ±(99.9%) 0.024 ms/op
Iteration   1: 5.621 ±(99.9%) 0.021 ms/op
Iteration   2: 5.655 ±(99.9%) 0.021 ms/op
Iteration   3: 00:37:32.226 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:32.231 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:32.231 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:32.232 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:32.233 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:37:32.234 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:32.235 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.245 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2983&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542991844&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.246 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.247 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.250 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=2983&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.250 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.250 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2983&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684542991844&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.250 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.250 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.251 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.252 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.253 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.254 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.255 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.255 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.255 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.255 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.255 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.256 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:34.264 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4ff269cc, dubbo version: 3.1.1, current host: 10.1.0.164
5.641 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.639 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (5.621, 5.639, 5.655), stdev = 0.018
  CI (99.9%): [5.319, 5.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 00:37:36.250 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.254 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.322 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.324 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.352 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.353 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.416 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.417 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.417 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.422 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.423 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.433 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.434 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.437 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.440 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.441 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7dc5b684, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.640 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:37:36.707 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:37:36.724 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:37:36.834 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.844 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:36.845 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.089 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:37:37.111 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.111 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.112 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.112 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.150 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.311 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:37:37.312 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:37:37.528 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.530 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.539 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.546 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.549 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.635 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:37:37.687 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543057618&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.688 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543057618&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.786 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.822 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543057618&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.824 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:37:37.829 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
7.024 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.919 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.648 ±(99.9%) 0.016 ms/op
Iteration   1: 4.567 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  13.830 ms/op
                 createUser·p0.9999: 22.183 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 4.543 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.833 ms/op
                 createUser·p0.95:   6.521 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  13.269 ms/op
                 createUser·p0.9999: 24.739 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 00:38:38.900 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:38.911 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:38.911 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:38.912 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:38.915 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:38:38.918 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:38.919 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.938 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543057618&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.939 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.943 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.944 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3073&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.944 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.944 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3073&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543057618&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.944 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.944 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.945 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.946 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.947 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.948 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.949 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.949 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.949 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.949 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.950 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.950 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.951 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.952 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:40.953 [org.apache.dubbo.benchmark.ClientGrpc.createUser-jmh-worker-19] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7dc5b684, dubbo version: 3.1.1, current host: 10.1.0.164
4.362 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.269 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  14.205 ms/op
                 createUser·p0.9999: 27.700 ms/op
                 createUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213763
  mean =      4.489 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5998 
    [ 2.500,  5.000) = 154821 
    [ 5.000,  7.500) = 48627 
    [ 7.500, 10.000) = 3300 
    [10.000, 12.500) = 716 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     13.754 ms/op
     p(99.9900) =     26.964 ms/op
     p(99.9990) =     29.974 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 00:38:43.117 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.120 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.178 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.179 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.202 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.203 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.260 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.261 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.261 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.267 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.267 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.279 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.279 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.282 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.285 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.285 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.500 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:38:43.566 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:38:43.590 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:38:43.773 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.789 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:43.790 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.054 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:38:44.088 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.089 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.089 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.090 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.130 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.308 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:38:44.309 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:38:44.592 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.603 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.617 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.627 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.632 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.718 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:38:44.777 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3235&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543124699&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.778 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3235&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543124699&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.891 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.931 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3235&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543124699&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.933 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:38:44.941 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
6.423 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.012 ms/op
Iteration   1: 4.233 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  12.403 ms/op
                 existUser·p0.9999: 16.562 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   2: 4.286 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   7.922 ms/op
                 existUser·p0.999:  11.585 ms/op
                 existUser·p0.9999: 20.170 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 00:39:45.986 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:45.991 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:45.991 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:45.992 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:45.992 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:39:45.993 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:45.994 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.004 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3235&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543124699&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.006 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.011 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.012 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3235&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.012 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.013 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3235&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543124699&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.013 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.013 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.014 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.015 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.016 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.016 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.017 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.017 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.017 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.017 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.018 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.018 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.018 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.019 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.019 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.019 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.019 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.019 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:48.023 [org.apache.dubbo.benchmark.ClientGrpc.existUser-jmh-worker-19] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
4.330 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   4.190 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   8.182 ms/op
                 existUser·p0.999:  13.774 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224147
  mean =      4.283 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7172 
    [ 2.500,  5.000) = 178817 
    [ 5.000,  7.500) = 34824 
    [ 7.500, 10.000) = 2628 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     12.826 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     25.966 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 00:39:50.146 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.150 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.235 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.237 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.264 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.265 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.327 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.328 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.328 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.334 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.335 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.347 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.347 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.351 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.355 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.355 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.552 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:39:50.598 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:39:50.616 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:39:50.753 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.765 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:50.767 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.053 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:39:51.088 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.089 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.090 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.091 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.138 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.330 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:39:51.331 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:39:51.565 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.567 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.585 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.595 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.600 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.688 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:39:51.770 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3392&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543191664&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.771 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3392&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543191664&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.879 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.916 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3392&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543191664&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.917 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:39:51.925 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
7.001 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.454 ±(99.9%) 0.015 ms/op
Iteration   1: 4.414 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  14.308 ms/op
                 getUser·p0.9999: 25.346 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 4.451 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 31.576 ms/op
                 getUser·p1.00:   32.997 ms/op

Iteration   3: 00:40:52.756 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:52.764 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:52.764 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:52.764 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:52.765 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:40:52.766 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:52.766 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.780 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3392&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543191664&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.781 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.782 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.783 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3392&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.783 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.783 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3392&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543191664&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.784 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.784 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.784 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.785 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.786 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.787 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.787 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.787 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.788 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.788 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.788 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.788 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.788 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.789 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.789 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.789 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.789 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.790 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:54.791 [org.apache.dubbo.benchmark.ClientGrpc.getUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
4.387 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  13.205 ms/op
                 getUser·p0.9999: 23.583 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217394
  mean =      4.417 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6269 
    [ 2.500,  5.000) = 165091 
    [ 5.000,  7.500) = 42562 
    [ 7.500, 10.000) = 2604 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     13.215 ms/op
     p(99.9900) =     30.647 ms/op
     p(99.9990) =     32.920 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 00:40:56.860 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:40:56.864 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:56.933 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:56.936 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:56.959 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:56.960 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.020 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.021 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.021 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.027 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.027 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.038 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.038 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.041 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.045 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.045 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.245 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:40:57.288 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:40:57.308 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:40:57.431 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.441 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.441 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has been initialized!, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.715 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService>] has been built.
00:40:57.748 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.749 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.749 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.750 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.773 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-grpc-client, entries 0, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:57.939 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.1, current host: 10.1.0.164
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
00:40:57.940 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.1, current host: 10.1.0.164
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
00:40:58.219 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService]. it's not GenericService reference, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.222 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.243 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.253 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.260 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.370 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.1, current host: 10.1.0.164, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:40:58.397 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3488&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543258334&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.398 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3488&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543258334&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.482 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyPortUnificationServer bind /0.0.0.0:20881, export /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.522 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3488&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543258334&version=1.0.0], dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.524 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.1, current host: 10.1.0.164
00:40:58.533 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is ready., dubbo version: 3.1.1, current host: 10.1.0.164
9.352 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 5.941 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.798 ±(99.9%) 0.024 ms/op
Iteration   1: 5.697 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   12.012 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 24.654 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   2: 5.956 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  23.626 ms/op
                 listUser·p0.9999: 28.750 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   3: 00:41:59.293 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:41:59.300 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:41:59.301 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-grpc-client) to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:41:59.301 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:41:59.302 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:41:59.303 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:41:59.304 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /0:0:0:0:0:0:0:0:20881, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.319 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.164:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&ispuserver=true&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3488&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543258334&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.320 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.321 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroying protocol [GrpcProtocol] ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.322 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.rpc.protocol.grpc.GrpcProtocol -  [DUBBO] Destroy reference: grpc://localhost:8080/org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService?application=dubbo-grpc-client&background=false&check=false&interface=org.apache.dubbo.benchmark.bean.DubboUserServiceGrpc$IUserService&pid=3488&protocol=grpc&register.ip=10.1.0.164&revision=1.0-SNAPSHOT&scope=remote&side=consumer&sticky=false&unloadClusterRelated=false, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.322 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.322 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-grpc-client&background=false&bind.ip=10.1.0.164&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-grpc-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3488&register=false&release=3.1.1&revision=3.1.1&side=provider&threadpool=cached&threads=100&timestamp=1684543258334&version=1.0.0, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.322 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.322 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.323 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.324 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.325 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-grpc-client) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.326 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.326 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.326 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.327 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.328 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.328 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.329 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.329 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.330 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.330 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.330 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.331 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.331 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.1, current host: 10.1.0.164
00:42:01.334 [org.apache.dubbo.benchmark.ClientGrpc.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.1, current host: 10.1.0.164
5.840 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   8.004 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   11.738 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 26.592 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164787
  mean =      5.829 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 341 
    [ 2.500,  5.000) = 55219 
    [ 5.000,  7.500) = 86809 
    [ 7.500, 10.000) = 17946 
    [10.000, 12.500) = 3216 
    [12.500, 15.000) = 738 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      8.012 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     11.864 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     31.547 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.103 ± 6.037  ops/ms
ClientGrpc.existUser                       thrpt       3   7.671 ± 1.209  ops/ms
ClientGrpc.getUser                         thrpt       3   7.138 ± 1.392  ops/ms
ClientGrpc.listUser                        thrpt       3   5.549 ± 2.012  ops/ms
ClientGrpc.createUser                       avgt       3   4.565 ± 1.403   ms/op
ClientGrpc.existUser                        avgt       3   4.251 ± 0.522   ms/op
ClientGrpc.getUser                          avgt       3   4.520 ± 1.449   ms/op
ClientGrpc.listUser                         avgt       3   5.639 ± 0.320   ms/op
ClientGrpc.createUser                     sample  213763   4.489 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.992           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.775           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.634           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.754           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.964           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.114           ms/op
ClientGrpc.existUser                      sample  224147   4.283 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.899           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.382           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.094           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.826           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.183           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  217394   4.417 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.083           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.218           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.348           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.215           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.647           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.997           ms/op
ClientGrpc.listUser                       sample  164787   5.829 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.364           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.012           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.864           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.217           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.689           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.389           ms/op
```
