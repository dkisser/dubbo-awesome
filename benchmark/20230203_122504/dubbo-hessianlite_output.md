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
[INFO] dubbo-hessianlite-client                                           [jar]
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
[INFO] -------------< org.apache.dubbo:dubbo-hessianlite-client >--------------
[INFO] Building dubbo-hessianlite-client 1.0-SNAPSHOT                     [4/4]
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ dubbo-hessianlite-client ---
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ dubbo-hessianlite-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 1 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ dubbo-hessianlite-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ dubbo-hessianlite-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ dubbo-hessianlite-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ dubbo-hessianlite-client ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-dependency-plugin:3.1.0:copy-dependencies (copy-dependencies) @ dubbo-hessianlite-client ---
[INFO] Copying client-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/client-base-1.0-SNAPSHOT.jar
[INFO] Copying benchmark-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/benchmark-base-1.0-SNAPSHOT.jar
[INFO] Copying protobuf-java-3.11.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/protobuf-java-3.11.0.jar
[INFO] Copying protobuf-java-util-3.11.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/protobuf-java-util-3.11.0.jar
[INFO] Copying guava-28.1-android.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/guava-28.1-android.jar
[INFO] Copying failureaccess-1.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/failureaccess-1.0.1.jar
[INFO] Copying listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
[INFO] Copying checker-compat-qual-2.5.5.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/checker-compat-qual-2.5.5.jar
[INFO] Copying j2objc-annotations-1.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/j2objc-annotations-1.3.jar
[INFO] Copying animal-sniffer-annotations-1.18.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/animal-sniffer-annotations-1.18.jar
[INFO] Copying error_prone_annotations-2.3.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/error_prone_annotations-2.3.3.jar
[INFO] Copying grpc-netty-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-netty-1.44.0.jar
[INFO] Copying grpc-core-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-core-1.44.0.jar
[INFO] Copying annotations-4.1.1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/annotations-4.1.1.4.jar
[INFO] Copying netty-codec-http2-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-http2-4.1.72.Final.jar
[INFO] Copying netty-common-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-common-4.1.72.Final.jar
[INFO] Copying netty-buffer-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-buffer-4.1.72.Final.jar
[INFO] Copying netty-transport-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-transport-4.1.72.Final.jar
[INFO] Copying netty-resolver-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-resolver-4.1.72.Final.jar
[INFO] Copying netty-codec-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-4.1.72.Final.jar
[INFO] Copying netty-handler-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-handler-4.1.72.Final.jar
[INFO] Copying netty-tcnative-classes-2.0.46.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-tcnative-classes-2.0.46.Final.jar
[INFO] Copying netty-codec-http-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-http-4.1.72.Final.jar
[INFO] Copying netty-handler-proxy-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-handler-proxy-4.1.72.Final.jar
[INFO] Copying netty-codec-socks-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-socks-4.1.72.Final.jar
[INFO] Copying perfmark-api-0.23.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/perfmark-api-0.23.0.jar
[INFO] Copying grpc-netty-shaded-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-netty-shaded-1.44.0.jar
[INFO] Copying grpc-protobuf-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-protobuf-1.44.0.jar
[INFO] Copying grpc-api-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-api-1.44.0.jar
[INFO] Copying grpc-context-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-context-1.44.0.jar
[INFO] Copying jsr305-3.0.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jsr305-3.0.2.jar
[INFO] Copying proto-google-common-protos-2.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/proto-google-common-protos-2.0.1.jar
[INFO] Copying grpc-protobuf-lite-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-protobuf-lite-1.44.0.jar
[INFO] Copying grpc-stub-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-stub-1.44.0.jar
[INFO] Copying jmh-core-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jmh-core-1.21.jar
[INFO] Copying jopt-simple-4.6.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jopt-simple-4.6.jar
[INFO] Copying commons-math3-3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/commons-math3-3.2.jar
[INFO] Copying jmh-generator-annprocess-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jmh-generator-annprocess-1.21.jar
[INFO] Copying dubbo-3.1.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.1.0.jar
[INFO] Copying spring-context-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-context-5.2.20.RELEASE.jar
[INFO] Copying spring-aop-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-aop-5.2.20.RELEASE.jar
[INFO] Copying spring-beans-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-beans-5.2.20.RELEASE.jar
[INFO] Copying spring-core-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-core-5.2.20.RELEASE.jar
[INFO] Copying spring-jcl-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-jcl-5.2.20.RELEASE.jar
[INFO] Copying spring-expression-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-expression-5.2.20.RELEASE.jar
[INFO] Copying spring-context-support-1.0.8.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-context-support-1.0.8.jar
[INFO] Copying javassist-3.28.0-GA.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/javassist-3.28.0-GA.jar
[INFO] Copying gson-2.8.9.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/gson-2.8.9.jar
[INFO] Copying snakeyaml-1.29.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/snakeyaml-1.29.jar
[INFO] Copying fastjson-1.2.83.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/fastjson-1.2.83.jar
[INFO] Copying fastjson2-2.0.7.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/fastjson2-2.0.7.jar
[INFO] Copying netty-all-4.1.25.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-all-4.1.25.Final.jar
[INFO] Copying slf4j-api-1.7.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/slf4j-api-1.7.25.jar
[INFO] Copying logback-classic-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/logback-classic-1.2.3.jar
[INFO] Copying logback-core-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/logback-core-1.2.3.jar
[INFO] Copying commons-cli-1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/commons-cli-1.4.jar
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ dubbo-hessianlite-client ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/dubbo-hessianlite-client-1.0-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for benchmark-base 1.0-SNAPSHOT:
[INFO] 
[INFO] benchmark-base ..................................... SUCCESS [  3.553 s]
[INFO] server-base ........................................ SUCCESS [  0.461 s]
[INFO] client-base ........................................ SUCCESS [  0.798 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  0.573 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.727 s
[INFO] Finished at: 2023-02-03T12:11:15Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-hessianlite-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-hessianlite-client/target/dubbo-hessianlite-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

[Ljava.lang.String;@6d03e736
# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:16.787 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.791 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.834 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.835 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.854 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.855 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.898 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.898 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.898 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.902 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.903 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.910 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.910 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.912 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.914 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:16.915 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7af24f92, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.066 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:17.098 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:17.126 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:17.206 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.217 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.218 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.412 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:17.436 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.437 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.438 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.439 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.473 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.608 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:17.609 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:17.690 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xd969ca55, L:/10.1.0.135:53986 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.692 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.692 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:53986 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.736 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.738 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.748 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.758 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.762 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.808 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.888 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2044&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426277803&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.888 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2044&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426277803&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.914 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.915 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2044&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426277803&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.916 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:17.921 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
0.747 ops/ms
Iteration   1: 12:11:20.018 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.020 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xd969ca55, L:/10.1.0.135:53986 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.022 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.023 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.023 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.023 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.026 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:53986 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.031 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.031 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:20.031 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.043 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.043 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.044 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2044&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426277803&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.045 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.045 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2044&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426277803&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.046 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.046 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.046 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.047 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.048 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.050 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.050 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.050 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.050 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.050 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.051 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.052 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.052 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.053 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.054 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.054 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.057 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.057 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:22.072 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7af24f92, dubbo version: 3.1.0, current host: 10.1.0.135
2.941 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.941 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:23.867 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.870 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.912 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.914 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.932 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.932 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.975 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.975 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.976 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.980 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.980 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.987 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.987 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.990 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.992 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:23.992 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.152 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:24.187 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:24.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:24.292 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.299 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.300 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.491 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:24.510 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.511 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.511 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.512 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.546 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:24.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:24.754 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:36690 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.755 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x4ec17047, L:/10.1.0.135:36690 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.756 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.780 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.781 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.790 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.796 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.797 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.824 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.958 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2329&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426284819&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.958 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2329&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426284819&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.967 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.968 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2329&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426284819&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.969 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:24.976 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
2.553 ops/ms
Iteration   1: 12:11:27.029 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.031 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x4ec17047, L:/10.1.0.135:36690 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.033 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.034 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.034 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.035 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.037 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:27.039 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:36690 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.055 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.055 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.056 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2329&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426284819&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.056 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2329&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426284819&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.058 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.059 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.059 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.066 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.066 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:29.067 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.135
5.425 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.425 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:30.884 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.888 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.933 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.934 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.994 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.994 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.994 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.998 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:30.999 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.008 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.010 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.011 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1586b105, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.158 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:31.203 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:31.247 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:31.329 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.335 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.336 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.521 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:31.537 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.537 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.538 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.538 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.557 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.688 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:31.688 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:31.772 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:36694 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.773 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x1940e4ab, L:/10.1.0.135:36694 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.773 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.790 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.791 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.800 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.805 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.806 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.834 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.916 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2413&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426291828&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.916 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2413&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426291828&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.929 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.933 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2413&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426291828&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.934 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:31.940 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
1.926 ops/ms
Iteration   1: 12:11:33.998 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.001 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1940e4ab, L:/10.1.0.135:36694 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.003 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:36694 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.005 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.013 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.016 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:34.017 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.039 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.039 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.040 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2413&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426291828&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.040 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2413&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426291828&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.042 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.048 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.048 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:36.049 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1586b105, dubbo version: 3.1.0, current host: 10.1.0.135
4.552 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.552 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:37.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.841 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.905 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.907 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.925 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.926 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.969 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.970 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.970 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.974 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.975 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.982 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.982 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.984 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.987 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:37.987 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.147 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:38.201 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:38.228 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:38.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.311 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.312 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.501 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:38.515 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.516 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.516 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.517 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.535 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.668 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:38.668 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:38.750 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x7de12f79, L:/10.1.0.135:56320 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.751 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.755 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:56320 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.779 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.781 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.798 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.803 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.804 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.959 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2494&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426298831&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.960 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2494&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426298831&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.977 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.981 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2494&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426298831&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.982 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:38.989 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
0.912 ops/ms
Iteration   1: 12:11:41.146 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.148 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x7de12f79, L:/10.1.0.135:56320 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.149 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:56320 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.150 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.151 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.151 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.151 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.153 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.154 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:41.154 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.180 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.181 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.181 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2494&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426298831&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2494&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426298831&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.184 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.185 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.187 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.187 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.187 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.187 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.188 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.188 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.195 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.195 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:43.196 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
1.401 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.401 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:44.972 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:44.975 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.024 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.026 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.043 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.044 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.085 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.086 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.086 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.090 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.092 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.102 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.102 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.104 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.107 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.107 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.269 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:45.327 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:45.375 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:45.478 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.493 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.494 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.689 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:45.703 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.704 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.704 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.704 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.723 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.849 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:45.849 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:45.930 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x00bae2b1, L:/10.1.0.135:54906 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.932 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.932 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:54906 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.955 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.956 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.966 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.971 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.972 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:45.999 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:46.108 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2573&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426305993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:46.109 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2573&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426305993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:46.121 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:46.122 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2573&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426305993&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:46.123 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:46.132 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
16.814 ±(99.9%) 0.343 ms/op
Iteration   1: 12:11:48.195 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.197 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x00bae2b1, L:/10.1.0.135:54906 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.199 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.199 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.199 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.199 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.202 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.204 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:54906 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.212 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:48.213 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.239 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.239 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.240 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2573&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426305993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.240 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.243 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2573&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426305993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.243 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.243 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.243 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.244 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.245 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.250 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.250 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:50.251 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
9.109 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.109 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:51.999 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.003 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.082 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.082 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.139 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.141 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.141 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.146 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.147 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.154 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.155 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.157 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.159 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.160 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.315 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:52.364 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:52.390 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:52.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.509 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.513 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.716 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:52.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.758 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.885 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:52.886 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:52.967 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:54920 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.968 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x162b72ce, L:/10.1.0.135:54920 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.968 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.987 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.989 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:52.998 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.004 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.005 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.032 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.127 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2656&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426313027&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.128 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2656&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426313027&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.135 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.136 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2656&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426313027&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.137 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:53.143 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
9.596 ±(99.9%) 0.151 ms/op
Iteration   1: 12:11:55.189 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.192 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x162b72ce, L:/10.1.0.135:54920 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.194 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.195 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.195 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.195 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.197 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.198 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.199 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:55.198 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:54920 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.208 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.208 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.209 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2656&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426313027&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.209 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.210 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2656&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426313027&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.210 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.210 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.211 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.211 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.212 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.218 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.218 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:57.219 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
4.673 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.673 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:59.005 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.008 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.054 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.055 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.073 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.074 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.116 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.116 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.116 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.120 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.121 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.127 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.128 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.130 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.132 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.132 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d9d103e, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.279 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:59.312 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:59.344 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:59.462 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.467 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.468 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.697 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:59.715 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.715 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.716 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.716 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.734 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.860 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:59.860 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:11:59.941 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:48124 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.941 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x8b2e4791, L:/10.1.0.135:48124 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.941 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.959 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.960 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.969 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:11:59.975 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.000 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.082 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2738&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426319996&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.082 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2738&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426319996&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.091 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.092 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2738&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426319996&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.093 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:00.099 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
9.174 ±(99.9%) 0.170 ms/op
Iteration   1: 12:12:02.145 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.147 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x8b2e4791, L:/10.1.0.135:48124 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.148 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:48124 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.152 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.152 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.152 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.153 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.154 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.160 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:02.161 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.176 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.177 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.177 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2738&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426319996&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.178 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.179 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2738&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426319996&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.179 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.179 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.180 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.180 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.181 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.186 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.186 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:04.187 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d9d103e, dubbo version: 3.1.0, current host: 10.1.0.135
5.041 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.041 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:06.007 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.010 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.070 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.071 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.090 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.090 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.134 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.134 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.135 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.139 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.139 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.146 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.147 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.150 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.153 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.153 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.324 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:06.361 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:06.388 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:06.475 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.482 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.487 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:06.723 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.723 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.724 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.724 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.743 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.876 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:06.877 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:06.990 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:51374 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.992 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x76172dbc, L:/10.1.0.135:51374 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:06.996 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.024 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.025 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.034 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.040 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.040 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.092 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.148 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2819&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426327087&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.149 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2819&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426327087&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.161 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.164 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2819&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426327087&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.165 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:07.170 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
30.510 ±(99.9%) 0.473 ms/op
Iteration   1: 12:12:09.283 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.286 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x76172dbc, L:/10.1.0.135:51374 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.289 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:51374 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.290 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.291 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:09.291 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.302 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.303 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2819&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426327087&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.303 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2819&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426327087&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.305 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.305 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.305 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.306 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.306 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.308 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.308 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.312 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.312 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.312 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.321 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.323 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:11.323 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
18.341 ±(99.9%) 0.116 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:13.121 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.124 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.172 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.174 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.191 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.192 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.235 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.235 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.235 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.239 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.240 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.249 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.252 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.252 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.423 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:13.478 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:13.504 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:13.580 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.586 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.587 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.790 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:13.806 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.806 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.807 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.808 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.827 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:13.956 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:13.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:14.042 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:49840 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.043 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xb37e907e, L:/10.1.0.135:49840 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.044 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.064 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.066 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.076 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.081 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.082 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.130 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.233 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2898&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426334124&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.234 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2898&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426334124&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2898&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426334124&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:14.253 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
13.515 ±(99.9%) 0.690 ms/op
Iteration   1: 12:12:16.370 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.372 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xb37e907e, L:/10.1.0.135:49840 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.374 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.374 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.375 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.375 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.376 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.377 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:49840 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.377 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:16.378 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.388 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.388 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.389 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2898&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426334124&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.389 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.390 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2898&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426334124&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.390 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.390 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.390 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.391 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.392 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.392 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.392 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.394 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.397 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:18.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-18] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.135
6.833 ±(99.9%) 0.123 ms/op
                 createUser·p0.00:   2.523 ms/op
                 createUser·p0.50:   6.865 ms/op
                 createUser·p0.90:   9.208 ms/op
                 createUser·p0.95:   11.416 ms/op
                 createUser·p0.99:   14.444 ms/op
                 createUser·p0.999:  27.503 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4663
  mean =      6.833 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1074 
    [ 5.000,  7.500) = 2772 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.523 ms/op
     p(50.0000) =      6.865 ms/op
     p(90.0000) =      9.208 ms/op
     p(95.0000) =     11.416 ms/op
     p(99.0000) =     14.444 ms/op
     p(99.9000) =     27.503 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:20.372 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.377 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.430 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.431 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.450 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.451 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.493 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.493 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.494 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.498 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.498 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.505 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.505 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.507 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.509 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.509 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.658 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:20.714 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:20.750 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:20.878 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.883 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:20.883 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.103 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:21.119 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.120 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.120 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.121 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.139 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:21.269 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:21.366 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:49848 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.368 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x2dd57c7f, L:/10.1.0.135:49848 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.368 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.395 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.396 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.406 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.411 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.412 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.561 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2979&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426341434&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.562 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2979&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426341434&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.571 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.572 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2979&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426341434&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.573 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:21.578 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
8.148 ±(99.9%) 0.257 ms/op
Iteration   1: 12:12:23.789 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.791 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x2dd57c7f, L:/10.1.0.135:49848 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.794 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.795 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.795 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:49848 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.801 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.801 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.803 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.803 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:23.803 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.812 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.813 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.813 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2979&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426341434&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.814 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.815 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2979&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426341434&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.815 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.815 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.815 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.816 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.817 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.819 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.819 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.819 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.825 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.825 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:25.826 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-24] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
4.600 ±(99.9%) 0.085 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   6.128 ms/op
                 existUser·p0.99:   13.730 ms/op
                 existUser·p0.999:  24.254 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6976
  mean =      4.600 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227 
    [ 2.500,  5.000) = 4382 
    [ 5.000,  7.500) = 2128 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =     13.730 ms/op
     p(99.9000) =     24.254 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:27.729 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.733 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.777 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.779 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.797 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.798 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.841 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.841 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.841 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.845 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.845 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.852 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.853 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.855 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.857 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:27.857 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.030 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:28.093 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:28.147 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:28.244 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.252 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.256 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.489 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:28.517 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.518 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.518 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.519 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.547 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.691 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:28.691 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:28.774 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x299ba36f, L:/10.1.0.135:50200 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.775 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.777 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:50200 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.800 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.802 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.817 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.818 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.844 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.946 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3061&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426348840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.946 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3061&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426348840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.955 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.956 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3061&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426348840&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.957 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:28.962 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
10.746 ±(99.9%) 0.394 ms/op
Iteration   1: 12:12:31.209 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.211 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x299ba36f, L:/10.1.0.135:50200 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.213 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:50200 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.213 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.214 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.220 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.220 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.221 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.221 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:31.222 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.233 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.234 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.234 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3061&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426348840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.235 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.236 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3061&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426348840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.236 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.236 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.236 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.237 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.238 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.238 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.239 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.240 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.240 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.240 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.245 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.246 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:33.247 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.135
4.715 ±(99.9%) 0.086 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   7.217 ms/op
                 getUser·p0.99:   19.068 ms/op
                 getUser·p0.999:  21.327 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6901
  mean =      4.715 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 5572 
    [ 5.000,  7.500) = 978 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     19.068 ms/op
     p(99.9000) =     21.327 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:35.209 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.212 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.272 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.273 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.291 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.292 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.341 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.341 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.341 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.345 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.346 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.353 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.353 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.356 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.358 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.358 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.512 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:35.547 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:35.574 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:35.671 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.684 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.688 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.891 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:35.909 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.910 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.910 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.911 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:35.930 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.056 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:36.056 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.135
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
12:12:36.145 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:48676 -> /10.1.0.135:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.146 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.135:8080 from NettyClient 10.1.0.135 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x1cf9a015, L:/10.1.0.135:48676 - R:/10.1.0.135:8080]], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.147 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.135 connect to the server /10.1.0.135:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.173 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.175 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.197 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.202 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.203 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.247 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.349 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3142&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426356233&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.350 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3142&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426356233&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.358 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.359 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3142&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426356233&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.360 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:36.366 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.135
33.877 ±(99.9%) 1.023 ms/op
Iteration   1: 12:12:38.547 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.549 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1cf9a015, L:/10.1.0.135:48676 - R:/10.1.0.135:8080], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.550 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.135:48676 -> /10.1.0.135:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.553 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.553 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.553 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.553 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.554 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.555 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:38.555 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.135:20880, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.562 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.135:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.563 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.564 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.135:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3142&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426356233&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.564 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.569 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.135&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3142&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675426356233&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.569 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.569 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.570 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.570 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.571 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.573 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.573 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.573 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.573 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.573 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.573 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.580 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.582 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.135
12:12:40.583 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.135
19.912 ±(99.9%) 0.377 ms/op
                 listUser·p0.00:   9.535 ms/op
                 listUser·p0.50:   19.595 ms/op
                 listUser·p0.90:   26.182 ms/op
                 listUser·p0.95:   30.966 ms/op
                 listUser·p0.99:   36.307 ms/op
                 listUser·p0.999:  37.054 ms/op
                 listUser·p0.9999: 37.487 ms/op
                 listUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1599
  mean =     19.912 ±(99.9%) 0.377 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 459 
    [20.000, 22.500) = 451 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      9.535 ms/op
     p(50.0000) =     19.595 ms/op
     p(90.0000) =     26.182 ms/op
     p(95.0000) =     30.966 ms/op
     p(99.0000) =     36.307 ms/op
     p(99.9000) =     37.054 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     37.487 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.941          ops/ms
Client.existUser                       thrpt         5.425          ops/ms
Client.getUser                         thrpt         4.552          ops/ms
Client.listUser                        thrpt         1.401          ops/ms
Client.createUser                       avgt         9.109           ms/op
Client.existUser                        avgt         4.673           ms/op
Client.getUser                          avgt         5.041           ms/op
Client.listUser                         avgt        18.341           ms/op
Client.createUser                     sample  4663   6.833 ± 0.123   ms/op
Client.createUser:createUser·p0.00    sample         2.523           ms/op
Client.createUser:createUser·p0.50    sample         6.865           ms/op
Client.createUser:createUser·p0.90    sample         9.208           ms/op
Client.createUser:createUser·p0.95    sample        11.416           ms/op
Client.createUser:createUser·p0.99    sample        14.444           ms/op
Client.createUser:createUser·p0.999   sample        27.503           ms/op
Client.createUser:createUser·p0.9999  sample        27.591           ms/op
Client.createUser:createUser·p1.00    sample        27.591           ms/op
Client.existUser                      sample  6976   4.600 ± 0.085   ms/op
Client.existUser:existUser·p0.00      sample         0.898           ms/op
Client.existUser:existUser·p0.50      sample         4.067           ms/op
Client.existUser:existUser·p0.90      sample         5.571           ms/op
Client.existUser:existUser·p0.95      sample         6.128           ms/op
Client.existUser:existUser·p0.99      sample        13.730           ms/op
Client.existUser:existUser·p0.999     sample        24.254           ms/op
Client.existUser:existUser·p0.9999    sample        25.625           ms/op
Client.existUser:existUser·p1.00      sample        25.625           ms/op
Client.getUser                        sample  6901   4.715 ± 0.086   ms/op
Client.getUser:getUser·p0.00          sample         1.399           ms/op
Client.getUser:getUser·p0.50          sample         4.317           ms/op
Client.getUser:getUser·p0.90          sample         5.857           ms/op
Client.getUser:getUser·p0.95          sample         7.217           ms/op
Client.getUser:getUser·p0.99          sample        19.068           ms/op
Client.getUser:getUser·p0.999         sample        21.327           ms/op
Client.getUser:getUser·p0.9999        sample        22.086           ms/op
Client.getUser:getUser·p1.00          sample        22.086           ms/op
Client.listUser                       sample  1599  19.912 ± 0.377   ms/op
Client.listUser:listUser·p0.00        sample         9.535           ms/op
Client.listUser:listUser·p0.50        sample        19.595           ms/op
Client.listUser:listUser·p0.90        sample        26.182           ms/op
Client.listUser:listUser·p0.95        sample        30.966           ms/op
Client.listUser:listUser·p0.99        sample        36.307           ms/op
Client.listUser:listUser·p0.999       sample        37.054           ms/op
Client.listUser:listUser·p0.9999      sample        37.487           ms/op
Client.listUser:listUser·p1.00        sample        37.487           ms/op
```
