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
[INFO] os.detected.version: 6.2
[INFO] os.detected.version.major: 6
[INFO] os.detected.version.minor: 2
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
[INFO] dubbo-triple-client                                                [jar]
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
[INFO] ----------------< org.apache.dubbo:dubbo-triple-client >----------------
[INFO] Building dubbo-triple-client 1.0-SNAPSHOT                          [4/4]
[INFO]   from ../dubbo-triple-client/pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ dubbo-triple-client ---
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ dubbo-triple-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 1 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ dubbo-triple-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ dubbo-triple-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ dubbo-triple-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ dubbo-triple-client ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-dependency-plugin:3.1.0:copy-dependencies (copy-dependencies) @ dubbo-triple-client ---
[INFO] Copying client-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/client-base-1.0-SNAPSHOT.jar
[INFO] Copying benchmark-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/benchmark-base-1.0-SNAPSHOT.jar
[INFO] Copying protobuf-java-3.11.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/protobuf-java-3.11.0.jar
[INFO] Copying protobuf-java-util-3.11.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/protobuf-java-util-3.11.0.jar
[INFO] Copying guava-28.1-android.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/guava-28.1-android.jar
[INFO] Copying failureaccess-1.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/failureaccess-1.0.1.jar
[INFO] Copying listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
[INFO] Copying checker-compat-qual-2.5.5.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/checker-compat-qual-2.5.5.jar
[INFO] Copying j2objc-annotations-1.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/j2objc-annotations-1.3.jar
[INFO] Copying animal-sniffer-annotations-1.18.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/animal-sniffer-annotations-1.18.jar
[INFO] Copying error_prone_annotations-2.3.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/error_prone_annotations-2.3.3.jar
[INFO] Copying grpc-netty-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-netty-1.44.0.jar
[INFO] Copying grpc-core-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-core-1.44.0.jar
[INFO] Copying annotations-4.1.1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/annotations-4.1.1.4.jar
[INFO] Copying netty-codec-http2-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-codec-http2-4.1.72.Final.jar
[INFO] Copying netty-common-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-common-4.1.72.Final.jar
[INFO] Copying netty-buffer-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-buffer-4.1.72.Final.jar
[INFO] Copying netty-transport-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-transport-4.1.72.Final.jar
[INFO] Copying netty-resolver-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-resolver-4.1.72.Final.jar
[INFO] Copying netty-codec-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-codec-4.1.72.Final.jar
[INFO] Copying netty-handler-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-handler-4.1.72.Final.jar
[INFO] Copying netty-tcnative-classes-2.0.46.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-tcnative-classes-2.0.46.Final.jar
[INFO] Copying netty-codec-http-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-codec-http-4.1.72.Final.jar
[INFO] Copying netty-handler-proxy-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-handler-proxy-4.1.72.Final.jar
[INFO] Copying netty-codec-socks-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-codec-socks-4.1.72.Final.jar
[INFO] Copying perfmark-api-0.23.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/perfmark-api-0.23.0.jar
[INFO] Copying grpc-netty-shaded-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-netty-shaded-1.44.0.jar
[INFO] Copying grpc-protobuf-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-protobuf-1.44.0.jar
[INFO] Copying grpc-api-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-api-1.44.0.jar
[INFO] Copying grpc-context-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-context-1.44.0.jar
[INFO] Copying jsr305-3.0.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/jsr305-3.0.2.jar
[INFO] Copying proto-google-common-protos-2.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/proto-google-common-protos-2.0.1.jar
[INFO] Copying grpc-protobuf-lite-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-protobuf-lite-1.44.0.jar
[INFO] Copying grpc-stub-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/grpc-stub-1.44.0.jar
[INFO] Copying jmh-core-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/jmh-core-1.21.jar
[INFO] Copying jopt-simple-4.6.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/jopt-simple-4.6.jar
[INFO] Copying commons-math3-3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/commons-math3-3.2.jar
[INFO] Copying jmh-generator-annprocess-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/jmh-generator-annprocess-1.21.jar
[INFO] Copying dubbo-3.1.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/dubbo-3.1.0.jar
[INFO] Copying spring-context-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-context-5.2.20.RELEASE.jar
[INFO] Copying spring-aop-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-aop-5.2.20.RELEASE.jar
[INFO] Copying spring-beans-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-beans-5.2.20.RELEASE.jar
[INFO] Copying spring-core-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-core-5.2.20.RELEASE.jar
[INFO] Copying spring-jcl-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-jcl-5.2.20.RELEASE.jar
[INFO] Copying spring-expression-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-expression-5.2.20.RELEASE.jar
[INFO] Copying spring-context-support-1.0.8.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/spring-context-support-1.0.8.jar
[INFO] Copying javassist-3.28.0-GA.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/javassist-3.28.0-GA.jar
[INFO] Copying gson-2.8.9.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/gson-2.8.9.jar
[INFO] Copying snakeyaml-1.29.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/snakeyaml-1.29.jar
[INFO] Copying fastjson-1.2.83.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/fastjson-1.2.83.jar
[INFO] Copying fastjson2-2.0.7.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/fastjson2-2.0.7.jar
[INFO] Copying netty-all-4.1.25.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/netty-all-4.1.25.Final.jar
[INFO] Copying slf4j-api-1.7.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/slf4j-api-1.7.25.jar
[INFO] Copying logback-classic-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/logback-classic-1.2.3.jar
[INFO] Copying logback-core-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/logback-core-1.2.3.jar
[INFO] Copying commons-cli-1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/commons-cli-1.4.jar
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ dubbo-triple-client ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for benchmark-base 1.0-SNAPSHOT:
[INFO] 
[INFO] benchmark-base ..................................... SUCCESS [  3.563 s]
[INFO] server-base ........................................ SUCCESS [  0.502 s]
[INFO] client-base ........................................ SUCCESS [  0.784 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.385 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.616 s
[INFO] Finished at: 2023-09-28T00:28:00Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-triple-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 00:28:02.010 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.020 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.104 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.105 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.148 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.148 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.149 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.153 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.153 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.160 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.161 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.163 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.165 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.166 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3a40f544, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.336 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:28:02.370 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:28:02.385 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:28:02.492 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.500 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.501 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.672 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:28:02.687 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.688 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.690 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.691 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.710 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.818 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.994 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:02.995 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.005 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.010 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.013 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.044 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.088 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.091 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2269&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860883036&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.092 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2269&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860883036&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.093 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.192 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.194 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2269&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860883036&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.194 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:28:03.202 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
2.160 ops/ms
# Warmup Iteration   2: 5.128 ops/ms
# Warmup Iteration   3: 8.469 ops/ms
Iteration   1: 9.008 ops/ms
Iteration   2: 9.087 ops/ms
Iteration   3: 00:29:03.326 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.329 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.329 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.329 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.332 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.333 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.333 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:03.334 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.350 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2269&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860883036&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.351 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.351 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2269&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860883036&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.351 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.351 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.352 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.352 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.352 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.353 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.359 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.365 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.365 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.372 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.374 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.376 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.377 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.377 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.377 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.378 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.378 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.379 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.380 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.380 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:05.381 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3a40f544, dubbo version: 3.1.0, current host: 10.1.0.107
8.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.024 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (8.977, 9.024, 9.087), stdev = 0.057
  CI (99.9%): [7.985, 10.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 00:29:08.130 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.134 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.179 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.180 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.199 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.200 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.244 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.245 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.245 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.250 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.250 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.257 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.258 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.260 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.263 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.263 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.429 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:29:08.463 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:29:08.478 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:29:08.573 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.589 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.595 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.774 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:29:08.789 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.790 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.794 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.794 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.825 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:08.919 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.080 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.083 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.099 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.108 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.111 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.158 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.198 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.210 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2816&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860949145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.211 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2816&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860949145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.213 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.308 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.309 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2816&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860949145&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.313 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:29:09.322 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
3.233 ops/ms
# Warmup Iteration   2: 8.546 ops/ms
# Warmup Iteration   3: 9.363 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 9.596 ops/ms
Iteration   3: 00:30:09.422 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.426 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.426 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.426 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.426 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.428 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:09.434 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.442 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2816&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860949145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.443 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.443 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2816&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695860949145&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.443 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.443 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.444 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.444 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.444 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.445 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.470 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.471 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.473 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.473 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.473 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.475 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.475 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:11.476 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
9.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.524 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (9.440, 9.524, 9.596), stdev = 0.079
  CI (99.9%): [8.081, 10.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:13.265 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.268 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.319 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.321 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.338 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.339 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.383 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.383 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.383 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.387 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.388 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.395 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.396 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.398 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.400 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.400 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.574 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:30:13.614 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:30:13.638 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:30:13.834 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.851 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:13.854 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.057 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:30:14.074 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.079 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.079 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.080 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.103 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.197 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.374 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.375 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.384 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.389 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.391 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.418 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.449 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3148&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861014411&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.450 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3148&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861014411&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.450 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.517 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3148&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861014411&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.522 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:30:14.530 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
2.793 ops/ms
# Warmup Iteration   2: 8.087 ops/ms
# Warmup Iteration   3: 9.029 ops/ms
Iteration   1: 9.149 ops/ms
Iteration   2: 9.289 ops/ms
Iteration   3: 00:31:14.636 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.639 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.639 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.640 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.640 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.641 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.642 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:14.643 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.653 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3148&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861014411&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.653 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.653 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3148&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861014411&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.654 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.654 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.654 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.655 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.656 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.657 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.673 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.674 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.675 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.675 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.676 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.677 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.677 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.677 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.678 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.679 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.679 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.679 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.680 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.680 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:16.681 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-24] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
9.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.162 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (9.047, 9.162, 9.289), stdev = 0.122
  CI (99.9%): [6.944, 11.379] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 00:31:18.510 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.513 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.579 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.580 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.599 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.599 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.653 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.653 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.653 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.657 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.658 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.665 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.665 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.668 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.670 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.671 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3a40f544, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:18.856 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:31:18.895 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:31:18.919 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:31:19.044 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.054 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.058 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.260 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:31:19.274 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.275 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.275 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.276 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.304 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.402 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.580 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.581 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.595 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.601 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.604 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.649 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.696 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.698 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3484&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861079634&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.699 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3484&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861079634&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.702 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.783 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.784 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3484&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861079634&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.785 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:31:19.791 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
2.510 ops/ms
# Warmup Iteration   2: 7.337 ops/ms
# Warmup Iteration   3: 7.510 ops/ms
Iteration   1: 7.571 ops/ms
Iteration   2: 7.569 ops/ms
Iteration   3: 00:32:19.907 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.911 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.915 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.916 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:19.917 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.930 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3484&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861079634&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.930 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.930 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3484&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861079634&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.930 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.930 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.931 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.944 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.954 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.954 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.956 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.956 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.956 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.956 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.958 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.958 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:21.960 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3a40f544, dubbo version: 3.1.0, current host: 10.1.0.107
7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.613 ±(99.9%) 1.346 ops/ms [Average]
  (min, avg, max) = (7.569, 7.613, 7.698), stdev = 0.074
  CI (99.9%): [6.267, 8.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 00:32:23.841 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.845 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.905 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.906 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.927 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.927 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.976 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.976 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.976 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.980 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.981 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.988 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.988 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.990 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.992 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:32:23.992 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.186 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:32:24.225 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:32:24.244 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:32:24.352 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.360 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.361 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.557 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:32:24.573 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.573 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.573 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.574 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.606 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.702 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.863 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.865 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.881 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.898 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.900 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:24.961 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.020 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.023 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861144952&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.024 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861144952&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.026 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.115 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.117 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861144952&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.117 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:32:25.124 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
10.470 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.004 ms/op
Iteration   1: 3.501 ±(99.9%) 0.008 ms/op
Iteration   2: 3.558 ±(99.9%) 0.005 ms/op
Iteration   3: 00:33:25.262 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.270 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.270 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.271 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.271 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.272 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.272 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:25.273 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.289 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861144952&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.289 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.289 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861144952&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.290 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.290 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.291 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.291 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.291 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.292 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.299 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.300 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.300 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.300 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.300 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.300 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.300 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.302 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.302 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.304 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.304 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.304 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.305 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.305 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:27.306 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
3.634 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.564 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (3.501, 3.564, 3.634), stdev = 0.066
  CI (99.9%): [2.355, 4.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 00:33:30.028 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.031 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.093 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.095 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.113 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.114 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.158 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.163 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.164 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.171 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.172 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.174 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.176 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.176 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.363 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:33:30.404 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:33:30.418 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:33:30.526 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.535 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.536 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.743 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:33:30.766 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.767 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.767 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.768 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.790 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:30.883 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.052 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.054 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.063 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.069 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.074 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.129 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.185 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.189 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4171&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861211112&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.189 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4171&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861211112&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.190 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.283 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.285 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4171&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861211112&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.286 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:33:31.292 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
8.682 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.006 ms/op
Iteration   1: 3.508 ±(99.9%) 0.011 ms/op
Iteration   2: 3.337 ±(99.9%) 0.004 ms/op
Iteration   3: 00:34:31.388 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.393 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.393 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.393 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.394 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.397 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.397 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:31.398 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.410 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4171&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861211112&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.410 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.410 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4171&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861211112&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.410 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.411 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.411 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.411 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.412 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.413 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.431 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.434 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.434 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.434 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.434 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.435 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.435 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.435 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.436 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.437 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:33.438 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-11] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
3.335 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.393 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (3.335, 3.393, 3.508), stdev = 0.099
  CI (99.9%): [1.583, 5.203] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 00:34:36.244 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.247 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.308 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.309 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.327 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.328 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.378 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.379 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.379 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.383 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.383 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.391 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.391 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.393 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.395 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.396 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3df62a95, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.573 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:34:36.608 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:34:36.623 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:34:36.758 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.766 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.772 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.963 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:34:36.978 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.978 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.978 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:36.979 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.006 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.102 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.278 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.279 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.288 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.298 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.301 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.332 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.393 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.396 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4510&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861277322&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.397 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4510&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861277322&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.399 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.495 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.496 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4510&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861277322&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.497 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:34:37.504 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
9.890 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.004 ms/op
Iteration   1: 3.558 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.003 ms/op
Iteration   3: 00:35:37.630 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.637 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.637 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:37.638 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.650 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4510&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861277322&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.651 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.651 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4510&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861277322&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.651 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.651 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.652 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.652 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.652 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.653 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.659 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.671 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.671 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.672 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.672 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.672 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.672 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.672 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.672 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.673 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.673 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.673 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.675 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.675 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:39.676 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3df62a95, dubbo version: 3.1.0, current host: 10.1.0.107
3.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.526 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.465, 3.526, 3.558), stdev = 0.053
  CI (99.9%): [2.558, 4.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 00:35:42.422 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.425 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.491 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.493 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.513 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.514 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.561 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.561 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.562 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.566 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.566 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.573 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.574 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.576 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.578 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.578 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.764 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:35:42.812 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:35:42.843 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:35:42.964 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.975 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:42.976 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.168 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:35:43.180 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.181 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.181 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.185 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.213 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.303 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.464 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.466 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.475 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.481 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.483 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.531 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.593 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.596 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4846&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861343520&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.597 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4846&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861343520&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.599 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.688 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.690 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4846&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861343520&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.691 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:35:43.697 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
10.444 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.009 ms/op
Iteration   1: 4.116 ±(99.9%) 0.007 ms/op
Iteration   2: 4.202 ±(99.9%) 0.010 ms/op
Iteration   3: 00:36:43.824 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.829 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.829 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.831 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.831 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.832 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.832 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:43.834 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.844 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4846&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861343520&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.845 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.845 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4846&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861343520&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.845 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.845 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.846 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.846 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.847 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.847 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.856 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.858 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.858 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.859 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.859 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.860 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.860 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.860 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.860 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.861 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.861 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.861 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.865 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.865 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:45.866 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-31] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
4.106 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.141 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (4.106, 4.141, 4.202), stdev = 0.053
  CI (99.9%): [3.172, 5.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 00:36:47.694 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.697 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.752 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.753 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.771 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.771 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.815 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.816 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.816 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.820 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.820 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.827 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.828 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.830 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.832 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:36:47.832 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@547dcb2f, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.021 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:36:48.067 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:36:48.087 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:36:48.212 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.226 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.227 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.425 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:36:48.437 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.438 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.438 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.438 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.458 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.548 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.705 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.706 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.720 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.733 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.741 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.798 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.842 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.844 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5175&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861408782&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.844 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5175&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861408782&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.845 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.933 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.935 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5175&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861408782&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.936 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:36:48.946 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
11.383 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.014 ms/op
Iteration   1: 3.535 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  20.218 ms/op
                 createUser·p0.9999: 23.362 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.648 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  21.931 ms/op
                 createUser·p0.9999: 24.573 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 00:37:49.505 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.511 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.511 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.511 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.512 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.514 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.515 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:49.516 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.523 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5175&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861408782&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.524 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.525 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5175&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861408782&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.525 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.525 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.526 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.527 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.527 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.528 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.542 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.545 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.545 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.545 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.546 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.546 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.546 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.546 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.546 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.547 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.548 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.548 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.549 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.549 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:51.552 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@547dcb2f, dubbo version: 3.1.0, current host: 10.1.0.107
3.556 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  18.420 ms/op
                 createUser·p0.9999: 27.755 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268171
  mean =      3.579 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4989 
    [ 2.500,  5.000) = 253109 
    [ 5.000,  7.500) = 8024 
    [ 7.500, 10.000) = 1324 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     26.554 ms/op
     p(99.9990) =     28.660 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 00:37:53.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.429 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.482 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.484 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.504 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.504 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.547 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.547 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.548 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.552 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.552 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.559 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.559 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.562 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.564 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.564 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.758 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:37:53.810 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:37:53.834 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:37:53.958 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.964 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:53.965 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.165 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:37:54.189 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.190 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.190 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.191 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.222 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.310 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.486 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.488 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.506 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.516 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.520 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.571 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.620 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.622 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5508&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861474558&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.622 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5508&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861474558&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.623 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.711 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.712 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5508&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861474558&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.713 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:37:54.719 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
9.081 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  14.793 ms/op
                 existUser·p0.9999: 19.012 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.308 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  16.520 ms/op
                 existUser·p0.9999: 19.672 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   3: 00:38:55.113 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.119 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.122 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.122 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.122 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:55.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.134 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5508&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861474558&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.134 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.135 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5508&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861474558&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.135 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.135 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.140 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.140 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.140 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.141 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.157 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.158 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.158 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.158 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.159 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.160 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.160 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.160 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.163 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.163 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:57.164 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
3.300 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  22.763 ms/op
                 existUser·p0.9999: 26.748 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287601
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4822 
    [ 2.500,  5.000) = 275581 
    [ 5.000,  7.500) = 5984 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     25.567 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 00:38:59.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.122 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.184 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.186 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.208 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.209 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.277 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.277 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.278 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.286 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.286 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.296 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.296 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.298 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.302 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.303 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.496 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:38:59.551 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:38:59.577 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:38:59.697 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.703 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.704 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.898 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:38:59.914 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.915 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.915 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.916 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:38:59.943 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.035 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.205 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.206 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.215 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.221 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.223 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.256 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.310 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.312 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861540246&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.313 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861540246&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.315 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.465 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.467 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861540246&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.468 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:39:00.479 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
11.290 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.012 ms/op
Iteration   1: 3.518 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 20.083 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.500 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  19.661 ms/op
                 getUser·p0.9999: 27.582 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   3: 00:40:01.240 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.244 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.244 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.245 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.245 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.249 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.249 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:01.250 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.261 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861540246&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.261 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.261 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5834&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861540246&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.262 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.262 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.262 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.263 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.263 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.264 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.273 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.276 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.277 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.277 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.279 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.279 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.280 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.282 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.282 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.283 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.283 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.283 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.284 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.285 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:03.286 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@43622f33, dubbo version: 3.1.0, current host: 10.1.0.107
3.563 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  17.924 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272067
  mean =      3.527 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2387 
    [ 2.500,  5.000) = 260847 
    [ 5.000,  7.500) = 6685 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 206 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     24.792 ms/op
     p(99.9990) =     30.359 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 00:40:06.060 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.063 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.108 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.109 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.127 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.128 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.174 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.175 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.175 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.180 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.181 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.188 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.188 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.190 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.194 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.194 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4d765f59, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.392 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:40:06.444 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:40:06.463 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:40:06.628 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.662 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.663 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.881 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:40:06.897 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.900 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.901 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.902 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:06.930 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.024 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.205 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.209 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.220 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.226 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.228 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.258 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.310 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.314 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=6223&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861607250&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.315 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=6223&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861607250&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.315 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.402 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.404 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=6223&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861607250&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.405 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.107
00:40:07.410 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.107
11.249 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.012 ms/op
Iteration   1: 4.221 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  17.374 ms/op
                 listUser·p0.9999: 20.997 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 4.217 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.677 ms/op
                 listUser·p0.9999: 24.079 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   3: 00:41:07.908 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.915 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.916 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:07.917 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.107:20881, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.943 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.107:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=6223&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861607250&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.943 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.943 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.107&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=6223&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1695861607250&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.943 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.943 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.944 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.944 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.945 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.946 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.953 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.956 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.957 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.958 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.959 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.960 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.960 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.961 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.962 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.962 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.968 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.968 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.107
00:41:09.974 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4d765f59, dubbo version: 3.1.0, current host: 10.1.0.107
4.098 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229585
  mean =      4.178 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 218262 
    [ 5.000,  7.500) = 8090 
    [ 7.500, 10.000) = 2277 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     16.474 ms/op
     p(99.9900) =     21.531 ms/op
     p(99.9990) =     24.360 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.024 ± 1.039  ops/ms
ClientPb.existUser                       thrpt       3   9.524 ± 1.443  ops/ms
ClientPb.getUser                         thrpt       3   9.162 ± 2.218  ops/ms
ClientPb.listUser                        thrpt       3   7.613 ± 1.346  ops/ms
ClientPb.createUser                       avgt       3   3.564 ± 1.210   ms/op
ClientPb.existUser                        avgt       3   3.393 ± 1.810   ms/op
ClientPb.getUser                          avgt       3   3.526 ± 0.968   ms/op
ClientPb.listUser                         avgt       3   4.141 ± 0.969   ms/op
ClientPb.createUser                     sample  268171   3.579 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.247           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.283           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.554           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.770           ms/op
ClientPb.existUser                      sample  287601   3.335 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.007           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.567           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.099           ms/op
ClientPb.getUser                        sample  272067   3.527 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.165           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.448           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.792           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  229585   4.178 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.897           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.474           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.531           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.952           ms/op
```
