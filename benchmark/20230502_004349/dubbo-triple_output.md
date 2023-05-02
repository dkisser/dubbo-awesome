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
[INFO] benchmark-base ..................................... SUCCESS [  3.925 s]
[INFO] server-base ........................................ SUCCESS [  0.500 s]
[INFO] client-base ........................................ SUCCESS [  0.808 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.657 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  6.443 s
[INFO] Finished at: 2023-05-02T00:30:06Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-triple-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:07.619 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.624 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.678 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.681 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.702 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.703 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.757 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.757 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.758 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.766 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.766 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.774 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.774 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.781 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.789 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:07.975 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:30:08.014 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:30:08.031 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:30:08.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.184 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.184 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.417 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:30:08.432 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.432 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.432 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.434 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.454 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.550 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.717 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.718 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.729 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.735 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.738 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.771 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.805 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.807 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2084&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987408762&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.807 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2084&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987408762&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.808 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.922 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.924 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2084&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987408762&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.925 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:30:08.933 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
1.851 ops/ms
# Warmup Iteration   2: 4.524 ops/ms
# Warmup Iteration   3: 8.270 ops/ms
Iteration   1: 8.401 ops/ms
Iteration   2: 8.334 ops/ms
Iteration   3: 00:31:09.044 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.048 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.048 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.052 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.052 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.054 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.054 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:09.055 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2084&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987408762&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2084&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987408762&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.071 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.072 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.072 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.072 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.073 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.085 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.085 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.087 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.087 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.087 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.088 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.088 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.092 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.092 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:11.098 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.0.143
8.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.366 ±(99.9%) 0.615 ops/ms [Average]
  (min, avg, max) = (8.334, 8.366, 8.401), stdev = 0.034
  CI (99.9%): [7.751, 8.980] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 00:31:12.999 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.002 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.050 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.052 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.076 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.077 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.126 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.131 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.131 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.138 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.139 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.141 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.143 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.144 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.327 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:31:13.362 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:31:13.379 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:31:13.529 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.548 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.552 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.744 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:31:13.757 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.758 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.758 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.759 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.778 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:13.871 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.061 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.063 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.073 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.079 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.081 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.119 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.167 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.169 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987474111&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.169 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987474111&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.170 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.260 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.262 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987474111&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.262 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:31:14.269 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
2.441 ops/ms
# Warmup Iteration   2: 7.871 ops/ms
# Warmup Iteration   3: 8.433 ops/ms
Iteration   1: 8.769 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 00:32:14.375 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.381 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.381 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.382 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.382 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.388 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.388 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:14.389 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.401 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987474111&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987474111&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.404 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.404 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.404 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.405 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.420 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.422 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.422 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.422 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.424 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.424 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.424 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.425 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.425 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:16.428 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.782 ±(99.9%) 8.933 ops/ms [Average]
  (min, avg, max) = (8.300, 8.782, 9.279), stdev = 0.490
  CI (99.9%): [≈ 0, 17.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 00:32:18.276 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.279 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.328 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.330 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.349 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.350 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.397 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.397 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.398 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.402 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.402 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.410 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.410 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.413 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.415 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.415 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@356efe27, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.594 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:32:18.628 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:32:18.643 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:32:18.775 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.787 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.787 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:18.994 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:32:19.012 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.013 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.013 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.014 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.041 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.152 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.319 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.321 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.331 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.337 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.339 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.370 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.428 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.430 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2895&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987539362&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.430 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2895&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987539362&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.432 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.529 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.531 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2895&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987539362&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.531 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:32:19.540 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
2.701 ops/ms
# Warmup Iteration   2: 7.840 ops/ms
# Warmup Iteration   3: 8.676 ops/ms
Iteration   1: 8.650 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 00:33:19.647 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.659 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.660 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.660 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.660 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.662 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.664 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:19.665 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.675 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2895&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987539362&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.678 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.678 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2895&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987539362&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.678 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.679 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.680 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.680 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.680 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.681 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.700 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.701 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.702 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.703 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.703 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.703 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.704 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.704 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.706 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.707 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.707 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.707 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.708 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.708 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:21.711 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-19] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@356efe27, dubbo version: 3.1.0, current host: 10.1.0.143
8.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.580 ±(99.9%) 2.926 ops/ms [Average]
  (min, avg, max) = (8.397, 8.580, 8.693), stdev = 0.160
  CI (99.9%): [5.654, 11.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 00:33:24.450 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.454 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.511 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.513 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.535 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.535 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.583 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.583 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.583 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.587 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.588 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.596 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.596 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.599 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.601 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.601 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2d25d6a6, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:24.811 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:33:24.868 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:33:24.888 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:33:25.028 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.042 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.046 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.214 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:33:25.235 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.235 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.235 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.236 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.256 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.352 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.536 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.538 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.548 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.554 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.556 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.590 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.654 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.656 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3191&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987605578&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.657 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3191&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987605578&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.659 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.749 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.751 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3191&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987605578&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.752 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:33:25.761 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
2.172 ops/ms
# Warmup Iteration   2: 6.355 ops/ms
# Warmup Iteration   3: 7.520 ops/ms
Iteration   1: 7.018 ops/ms
Iteration   2: 7.409 ops/ms
Iteration   3: 00:34:25.897 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.902 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.903 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.903 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.904 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.910 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.911 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:25.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3191&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987605578&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3191&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987605578&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.934 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.934 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.935 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.948 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.951 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.952 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.952 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.952 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.952 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.952 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.952 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.953 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.953 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.953 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.953 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.955 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:27.956 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2d25d6a6, dubbo version: 3.1.0, current host: 10.1.0.143
7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.362 ±(99.9%) 5.886 ops/ms [Average]
  (min, avg, max) = (7.018, 7.362, 7.658), stdev = 0.323
  CI (99.9%): [1.476, 13.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 00:34:30.742 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.746 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.795 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.818 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.818 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.865 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.866 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.866 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.870 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.871 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.878 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.879 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.881 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.884 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:34:30.884 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.064 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:34:31.101 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:34:31.117 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:34:31.235 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.244 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.251 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.443 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:34:31.457 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.457 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.458 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.458 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.496 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.597 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.765 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.767 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.776 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.782 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.785 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.818 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.849 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.850 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3545&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987671809&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.850 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3545&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987671809&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.851 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.949 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.950 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3545&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987671809&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.951 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:34:31.960 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
11.699 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.006 ms/op
Iteration   1: 3.783 ±(99.9%) 0.010 ms/op
Iteration   2: 3.632 ±(99.9%) 0.011 ms/op
Iteration   3: 00:35:32.077 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.082 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.082 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.082 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.082 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:32.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.096 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3545&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987671809&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.098 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.098 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3545&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987671809&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.098 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.098 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.099 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.099 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.099 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.100 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.110 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.110 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.111 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.112 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.119 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.119 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.119 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.119 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.121 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.121 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.121 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.121 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.123 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.123 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:34.125 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
3.615 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.677 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (3.615, 3.677, 3.783), stdev = 0.092
  CI (99.9%): [1.990, 5.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 00:35:36.931 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:35:36.936 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:36.989 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:36.990 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.010 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.010 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.058 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.058 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.058 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.062 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.063 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.071 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.071 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.073 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.076 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.076 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.264 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:35:37.300 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:35:37.316 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:35:37.425 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.433 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.643 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:35:37.657 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.658 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.658 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.659 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.678 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.777 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.945 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.947 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.956 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.961 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:37.963 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.005 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.065 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.067 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3836&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987737993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.069 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3836&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987737993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.071 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.174 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.176 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3836&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987737993&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.177 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:35:38.186 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
10.914 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.006 ms/op
Iteration   1: 3.495 ±(99.9%) 0.010 ms/op
Iteration   2: 3.423 ±(99.9%) 0.010 ms/op
Iteration   3: 00:36:38.303 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.312 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.312 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.312 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.312 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.319 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.319 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:38.320 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.333 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3836&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987737993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.333 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.334 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3836&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987737993&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.334 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.334 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.335 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.335 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.335 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.337 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.344 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.349 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.350 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.350 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.351 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.354 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.354 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.354 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.354 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.355 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.356 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.356 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.362 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.362 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:40.370 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
3.489 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.469 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.423, 3.469, 3.495), stdev = 0.040
  CI (99.9%): [2.734, 4.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 00:36:42.211 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.214 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.260 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.261 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.281 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.282 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.329 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.330 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.330 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.335 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.335 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.343 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.343 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.346 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.348 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.349 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.538 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:36:42.572 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:36:42.604 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:36:42.713 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.733 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.735 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.937 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:36:42.955 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.956 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.956 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.956 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:42.980 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.087 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.266 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.267 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.277 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.283 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.285 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.332 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.366 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.367 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4130&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987803324&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.368 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4130&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987803324&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.368 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.456 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.458 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4130&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987803324&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.459 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:36:43.465 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
11.176 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.004 ms/op
Iteration   1: 3.641 ±(99.9%) 0.008 ms/op
Iteration   2: 3.763 ±(99.9%) 0.006 ms/op
Iteration   3: 00:37:43.586 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.594 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.594 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.594 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.594 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.597 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.597 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:43.598 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.607 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4130&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987803324&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.609 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.609 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4130&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987803324&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.609 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.609 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.610 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.610 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.610 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.611 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.631 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.633 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.633 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.633 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.633 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.635 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.635 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.635 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.637 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.637 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:45.638 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
3.670 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.691 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (3.641, 3.691, 3.763), stdev = 0.064
  CI (99.9%): [2.528, 4.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 00:37:47.475 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.481 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.544 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.546 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.566 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.567 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.611 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.612 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.612 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.616 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.616 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.624 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.624 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.626 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.629 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.629 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:47.807 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:37:47.842 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:37:47.881 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:37:48.006 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.023 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.024 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.204 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:37:48.216 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.217 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.217 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.217 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.236 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.329 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.518 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.519 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.531 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.544 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.546 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.575 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.620 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.623 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4421&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987868567&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.623 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4421&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987868567&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.624 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.698 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.700 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4421&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987868567&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.701 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:37:48.708 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
12.651 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.245 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.007 ms/op
Iteration   1: 4.412 ±(99.9%) 0.008 ms/op
Iteration   2: 4.307 ±(99.9%) 0.014 ms/op
Iteration   3: 00:38:48.837 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.843 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.843 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.844 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.844 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.845 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.849 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:48.851 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.862 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4421&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987868567&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.863 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.863 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4421&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987868567&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.863 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.863 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.864 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.864 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.865 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.866 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.872 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.882 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.882 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.883 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.884 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.885 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.886 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.886 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.886 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.887 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.887 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.887 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.888 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.888 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:50.889 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.0.143
4.276 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.332 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (4.276, 4.332, 4.412), stdev = 0.071
  CI (99.9%): [3.033, 5.630] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 00:38:52.710 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.714 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.776 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.778 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.850 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.850 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.850 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.855 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.855 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.863 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.863 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.865 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.868 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:38:52.868 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.054 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:38:53.095 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:38:53.123 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:38:53.271 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.281 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.287 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.483 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:38:53.497 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.497 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.497 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.498 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.521 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.630 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.807 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.809 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.819 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.825 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.828 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.859 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.919 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.922 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4709&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987933850&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.922 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4709&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987933850&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:53.924 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:54.018 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:38:54.020 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4709&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987933850&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:38:54.023 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:38:54.028 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
10.908 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.017 ms/op
Iteration   1: 3.657 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  23.221 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   2: 3.751 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.631 ms/op
                 createUser·p0.999:  15.741 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 00:39:55.016 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.021 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.021 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.022 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.027 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.030 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.031 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:55.032 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.044 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4709&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987933850&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.044 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.045 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4709&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682987933850&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.045 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.045 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.046 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.046 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.046 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.047 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.052 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.062 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.062 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.063 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.063 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.065 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.066 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.066 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.067 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.071 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.071 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.071 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.072 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.073 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:57.074 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-32] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.0.143
3.675 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  29.000 ms/op
                 createUser·p0.9999: 33.115 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 259660
  mean =      3.694 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2355 
    [ 2.500,  5.000) = 249519 
    [ 5.000,  7.500) = 6580 
    [ 7.500, 10.000) = 670 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     21.743 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.469 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 00:39:58.975 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:39:58.978 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.022 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.024 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.043 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.043 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.089 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.089 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.089 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.093 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.093 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.100 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.101 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.103 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.106 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.106 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.285 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:39:59.321 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:39:59.343 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:39:59.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.480 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.481 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.714 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:39:59.736 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.738 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.739 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.739 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.779 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:39:59.873 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.032 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.034 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.044 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.050 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.053 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.097 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.176 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.179 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5057&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988000090&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.180 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5057&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988000090&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.181 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.268 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.270 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5057&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988000090&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.271 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:40:00.276 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
10.998 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.010 ms/op
Iteration   1: 3.517 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  19.628 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 3.559 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.897 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 00:41:00.720 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.728 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.728 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.729 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.729 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.731 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.733 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:00.738 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.750 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5057&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988000090&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.751 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.751 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5057&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988000090&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.751 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.751 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.752 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.752 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.753 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.754 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.773 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.774 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.774 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.774 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.774 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.775 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.775 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.775 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.775 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.775 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.776 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.776 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.777 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.777 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:02.782 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.0.143
3.529 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  23.249 ms/op
                 existUser·p0.9999: 27.359 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271658
  mean =      3.535 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1813 
    [ 2.500,  5.000) = 262516 
    [ 5.000,  7.500) = 6415 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     12.359 ms/op
     p(99.9900) =     26.007 ms/op
     p(99.9990) =     28.611 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 00:41:05.615 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.618 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.674 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.676 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.696 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.697 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.745 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.746 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.746 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.750 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.751 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.758 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.759 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.762 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.764 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.765 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@356efe27, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:05.958 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:41:05.997 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:41:06.014 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:41:06.146 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.159 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.159 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.386 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:41:06.404 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.405 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.405 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.406 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.428 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.531 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.713 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.714 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.725 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.731 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.733 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.767 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.836 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.839 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5346&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988066756&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.839 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5346&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988066756&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.841 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.975 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.977 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5346&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988066756&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.978 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:41:06.989 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
10.926 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.013 ms/op
Iteration   1: 3.783 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  19.622 ms/op
                 getUser·p0.9999: 27.245 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   2: 3.717 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  25.559 ms/op
                 getUser·p0.9999: 28.043 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   3: 00:42:07.443 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.452 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.457 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:07.459 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.471 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5346&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988066756&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.473 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.473 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5346&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988066756&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.473 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.473 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.474 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.474 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.475 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.475 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.518 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.519 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.520 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.520 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.520 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.521 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.521 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.522 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.522 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:09.523 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@356efe27, dubbo version: 3.1.0, current host: 10.1.0.143
3.833 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.812 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  10.888 ms/op
                 getUser·p0.9999: 29.764 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 253960
  mean =      3.777 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1865 
    [ 2.500,  5.000) = 237018 
    [ 5.000,  7.500) = 13094 
    [ 7.500, 10.000) = 1465 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     19.042 ms/op
     p(99.9900) =     28.561 ms/op
     p(99.9990) =     30.275 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 00:42:11.370 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.373 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.428 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.430 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.453 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.453 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.508 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.508 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.510 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.517 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.518 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.525 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.525 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.527 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.530 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.530 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.714 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
00:42:11.748 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
00:42:11.763 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
00:42:11.906 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.914 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:11.915 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.105 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
00:42:12.120 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.121 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.121 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.122 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.141 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.239 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.426 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.428 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.438 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.444 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.447 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.485 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.541 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.572 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5644&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988132471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.572 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5644&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988132471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.573 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.670 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.672 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5644&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988132471&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.673 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.143
00:42:12.681 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.143
12.246 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 5.090 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.017 ms/op
Iteration   1: 4.332 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  24.181 ms/op
                 listUser·p0.9999: 28.235 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.523 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.883 ms/op
                 listUser·p0.9999: 19.000 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 00:43:13.523 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.528 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.529 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.529 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.529 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.532 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.532 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:13.533 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.143:20881, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.552 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.143:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5644&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988132471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.552 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.552 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.143&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5644&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1682988132471&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.552 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.552 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.553 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.553 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.554 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.555 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.572 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.574 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.574 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.574 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.581 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.582 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.582 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.582 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.582 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.583 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.583 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.583 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.586 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.586 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.143
00:43:15.587 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.143
4.447 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.662 ms/op
                 listUser·p0.9999: 20.539 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 216582
  mean =      4.433 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 197117 
    [ 5.000,  7.500) = 15610 
    [ 7.500, 10.000) = 2888 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     29.366 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.366 ± 0.615  ops/ms
ClientPb.existUser                       thrpt       3   8.782 ± 8.933  ops/ms
ClientPb.getUser                         thrpt       3   8.580 ± 2.926  ops/ms
ClientPb.listUser                        thrpt       3   7.362 ± 5.886  ops/ms
ClientPb.createUser                       avgt       3   3.677 ± 1.686   ms/op
ClientPb.existUser                        avgt       3   3.469 ± 0.735   ms/op
ClientPb.getUser                          avgt       3   3.691 ± 1.163   ms/op
ClientPb.listUser                         avgt       3   4.332 ± 1.299   ms/op
ClientPb.createUser                     sample  259660   3.694 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.374           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.743           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  271658   3.535 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.359           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.007           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.869           ms/op
ClientPb.getUser                        sample  253960   3.777 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.031           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.042           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.561           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.999           ms/op
ClientPb.listUser                       sample  216582   4.433 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.531           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
```
