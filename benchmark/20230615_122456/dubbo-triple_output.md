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
[INFO] benchmark-base ..................................... SUCCESS [  4.728 s]
[INFO] server-base ........................................ SUCCESS [  0.639 s]
[INFO] client-base ........................................ SUCCESS [  1.119 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.551 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  7.596 s
[INFO] Finished at: 2023-06-15T12:11:09Z
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
# Warmup Iteration   1: 12:11:10.518 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.523 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.580 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.581 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.606 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.606 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.660 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.660 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.660 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.666 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.666 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.676 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.676 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.683 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.686 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.686 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:10.929 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:11.011 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:11.038 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:11.187 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.197 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.199 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.416 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:11.435 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.436 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.438 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.438 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.462 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.574 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.775 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.777 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.787 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.793 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.855 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.955 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.960 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2231&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831071840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.961 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2231&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831071840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:11.962 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:12.078 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:11:12.079 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2231&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831071840&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:11:12.081 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:11:12.095 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
0.960 ops/ms
# Warmup Iteration   2: 2.050 ops/ms
# Warmup Iteration   3: 4.674 ops/ms
Iteration   1: 5.301 ops/ms
Iteration   2: 5.462 ops/ms
Iteration   3: 12:12:12.311 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.317 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.317 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.318 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.318 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.323 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.323 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:12.324 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.341 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2231&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831071840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.341 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.342 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2231&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831071840&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.342 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.342 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.343 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.343 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.344 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.345 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.365 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.369 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.369 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.369 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.370 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.370 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.370 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.371 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.372 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.373 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.373 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.373 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.375 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.375 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:14.376 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.467 ±(99.9%) 3.082 ops/ms [Average]
  (min, avg, max) = (5.301, 5.467, 5.639), stdev = 0.169
  CI (99.9%): [2.385, 8.549] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:17.369 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.373 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.473 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.476 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.501 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.501 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.556 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.556 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.556 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.562 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.562 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.572 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.572 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.575 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.578 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.578 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:17.803 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:17.850 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:17.876 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:18.027 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.044 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.044 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.267 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:18.284 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.284 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.284 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.285 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.311 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.424 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.628 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.631 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.644 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.650 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.654 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.702 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.763 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.768 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2742&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831138684&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.768 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2742&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831138684&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.771 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.883 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.885 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2742&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831138684&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.886 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:12:18.899 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
1.576 ops/ms
# Warmup Iteration   2: 4.720 ops/ms
# Warmup Iteration   3: 5.663 ops/ms
Iteration   1: 5.715 ops/ms
Iteration   2: 5.739 ops/ms
Iteration   3: 12:13:19.056 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.061 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.062 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.062 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.062 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.066 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.066 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:19.070 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.080 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2742&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831138684&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.082 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.082 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2742&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831138684&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.082 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.082 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.083 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.083 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.084 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.085 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.109 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.111 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.111 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.111 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.115 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.115 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.116 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.116 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.116 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.117 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.118 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.118 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.120 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.120 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:21.123 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-29] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
5.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.802 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (5.715, 5.802, 5.952), stdev = 0.131
  CI (99.9%): [3.419, 8.185] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 12:13:24.065 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.071 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.142 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.144 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.169 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.170 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.237 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.237 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.237 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.244 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.244 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.255 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.256 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.259 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.263 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.263 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.489 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:13:24.532 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:13:24.553 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:13:24.730 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.750 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.757 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:24.988 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:13:25.007 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.008 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.008 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.009 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.046 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.181 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.421 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.424 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.437 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.445 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.492 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.571 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.574 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3039&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831205480&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.575 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3039&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831205480&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.577 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.694 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.696 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3039&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831205480&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.697 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:13:25.715 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
1.487 ops/ms
# Warmup Iteration   2: 4.037 ops/ms
# Warmup Iteration   3: 5.533 ops/ms
Iteration   1: 5.489 ops/ms
Iteration   2: 5.445 ops/ms
Iteration   3: 12:14:25.869 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.877 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.878 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.878 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.878 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.886 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.886 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:25.887 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.908 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3039&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831205480&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.908 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.909 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3039&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831205480&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.909 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.909 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.910 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.910 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.910 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.911 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.919 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.931 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.931 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.932 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.932 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.932 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.932 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.933 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.933 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.934 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.934 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.934 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.936 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.937 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:27.940 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
5.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.464 ±(99.9%) 0.410 ops/ms [Average]
  (min, avg, max) = (5.445, 5.464, 5.489), stdev = 0.022
  CI (99.9%): [5.054, 5.874] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 12:14:30.902 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:14:30.906 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:30.962 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:30.964 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:30.992 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:30.993 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.052 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.053 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.053 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.059 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.060 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.071 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.071 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.075 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.078 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.079 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7dc5b684, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.321 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:14:31.373 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:14:31.394 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:14:31.526 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.537 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.538 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.804 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:14:31.837 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.837 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.838 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.839 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.875 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:31.995 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.213 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.215 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.227 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.237 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.281 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.323 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.326 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3332&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831272269&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.326 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3332&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831272269&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.327 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.417 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.418 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3332&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831272269&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:14:32.434 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
1.428 ops/ms
# Warmup Iteration   2: 3.672 ops/ms
# Warmup Iteration   3: 4.503 ops/ms
Iteration   1: 4.692 ops/ms
Iteration   2: 4.694 ops/ms
Iteration   3: 12:15:32.607 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.615 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.615 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.615 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.616 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.618 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.618 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:32.619 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.631 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3332&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831272269&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.632 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.632 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3332&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831272269&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.633 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.633 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.634 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.634 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.634 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.635 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.647 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.649 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.649 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.650 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.650 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.650 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.650 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.651 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.651 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.655 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.656 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.657 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.664 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.664 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:34.666 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7dc5b684, dubbo version: 3.1.0, current host: 10.1.54.1
4.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.695 ±(99.9%) 0.071 ops/ms [Average]
  (min, avg, max) = (4.692, 4.695, 4.700), stdev = 0.004
  CI (99.9%): [4.625, 4.766] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 12:15:37.715 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.721 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.801 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.804 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.833 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.834 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.899 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.899 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.900 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.906 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.906 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.926 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.926 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.929 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.932 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:15:37.933 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.171 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:15:38.229 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:15:38.250 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:15:38.450 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.474 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.477 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.729 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:15:38.745 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.746 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.746 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.747 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.779 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:38.901 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.140 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.142 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.153 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.162 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.165 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.228 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.317 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.320 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3687&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831339210&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.321 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3687&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831339210&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.322 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.452 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.454 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3687&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831339210&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.455 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:15:39.464 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
20.181 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.248 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.881 ±(99.9%) 0.013 ms/op
Iteration   1: 5.928 ±(99.9%) 0.015 ms/op
Iteration   2: 5.878 ±(99.9%) 0.009 ms/op
Iteration   3: 12:16:39.626 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.636 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.637 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.637 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.637 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.639 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.640 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:39.641 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.654 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3687&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831339210&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.654 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.655 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3687&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831339210&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.655 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.655 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.656 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.657 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.657 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.659 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.686 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.687 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.688 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.688 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.688 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.688 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.689 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.690 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.690 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.691 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.692 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.692 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.694 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.694 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:41.695 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4bd084b7, dubbo version: 3.1.0, current host: 10.1.54.1
5.771 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.859 ±(99.9%) 1.468 ms/op [Average]
  (min, avg, max) = (5.771, 5.859, 5.928), stdev = 0.080
  CI (99.9%): [4.391, 7.327] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 12:16:44.715 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.719 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.792 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.794 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.820 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.821 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.881 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.882 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.882 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.888 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.888 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.898 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.898 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.903 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.909 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:16:44.909 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.147 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:16:45.204 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:16:45.225 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:16:45.417 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.430 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.436 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.666 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:16:45.701 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.702 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.703 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.704 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.743 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:45.867 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.086 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.088 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.099 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.106 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.109 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.149 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.193 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.195 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3986&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831406137&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.196 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3986&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831406137&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.197 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.303 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.307 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3986&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831406137&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.308 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:16:46.321 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
17.739 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.293 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.742 ±(99.9%) 0.007 ms/op
Iteration   1: 5.490 ±(99.9%) 0.009 ms/op
Iteration   2: 5.399 ±(99.9%) 0.017 ms/op
Iteration   3: 12:17:46.490 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.494 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.494 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.494 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.495 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.496 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.497 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:46.500 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.516 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3986&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831406137&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.517 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.517 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3986&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831406137&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.517 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.517 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.518 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.518 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.519 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.521 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.535 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.544 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.547 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.547 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.547 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.547 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.548 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.548 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.548 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.549 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.549 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.549 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.558 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.559 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:48.561 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
5.406 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.431 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (5.399, 5.431, 5.490), stdev = 0.050
  CI (99.9%): [4.512, 6.351] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 12:17:51.531 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.538 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.618 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.620 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.642 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.643 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.701 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.701 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.701 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.707 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.707 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.718 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.718 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.722 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.725 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.725 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:51.957 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:17:52.037 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:17:52.085 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:17:52.267 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.276 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.277 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.532 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:17:52.556 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.557 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.557 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.558 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.591 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.708 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.911 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.913 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.925 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.933 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.938 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:52.996 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.063 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.070 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4275&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831472985&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.070 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4275&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831472985&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.071 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.199 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.201 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4275&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831472985&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.202 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:17:53.211 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
19.216 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.072 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.733 ±(99.9%) 0.013 ms/op
Iteration   1: 5.721 ±(99.9%) 0.008 ms/op
Iteration   2: 5.721 ±(99.9%) 0.019 ms/op
Iteration   3: 12:18:53.362 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.377 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.377 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.377 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.378 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.380 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.381 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:53.382 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.407 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4275&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831472985&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.408 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.408 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4275&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831472985&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.408 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.408 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.409 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.409 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.410 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.411 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.449 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.451 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.451 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.451 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.452 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.452 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.452 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.452 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.452 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.453 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.453 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.453 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.458 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.459 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:55.460 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
5.835 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.759 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (5.721, 5.759, 5.835), stdev = 0.066
  CI (99.9%): [4.562, 6.956] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 12:18:57.429 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.433 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.511 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.513 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.537 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.538 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.598 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.598 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.599 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.604 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.605 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.615 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.615 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.618 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.621 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.621 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:57.846 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:18:57.894 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:18:57.919 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:18:58.080 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.089 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.090 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.371 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:18:58.413 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.414 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.417 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.418 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.461 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.574 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.791 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.793 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.804 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.812 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.815 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.854 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.925 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4564&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831538844&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.932 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4564&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831538844&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:58.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:59.046 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:18:59.048 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4564&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831538844&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:18:59.052 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:18:59.058 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
20.950 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 8.146 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.914 ±(99.9%) 0.012 ms/op
Iteration   1: 6.846 ±(99.9%) 0.009 ms/op
Iteration   2: 6.748 ±(99.9%) 0.014 ms/op
Iteration   3: 12:19:59.229 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.242 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.242 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.242 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.242 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.246 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.247 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:19:59.248 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.259 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4564&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831538844&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.260 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.260 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4564&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831538844&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.260 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.260 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.261 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.262 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.262 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.263 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.279 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.285 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.287 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.287 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.288 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.288 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.290 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.290 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:01.291 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
6.917 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.837 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (6.748, 6.837, 6.917), stdev = 0.085
  CI (99.9%): [5.292, 8.382] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 12:20:04.315 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.318 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.385 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.387 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.410 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.411 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.471 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.472 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.472 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.478 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.479 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.490 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.490 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.494 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.497 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.497 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.725 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:20:04.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:20:04.809 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:20:04.969 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.982 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:04.986 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.269 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:20:05.291 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.292 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.292 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.295 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.331 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.461 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.678 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.680 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.692 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.699 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.702 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.752 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.795 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.801 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4853&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831605740&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.801 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4853&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831605740&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.802 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.934 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.936 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4853&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831605740&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.937 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:20:05.945 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
18.494 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 8.220 ±(99.9%) 0.068 ms/op
# Warmup Iteration   3: 6.625 ±(99.9%) 0.034 ms/op
Iteration   1: 5.839 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.075 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  25.960 ms/op
                 createUser·p0.9999: 32.200 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   2: 5.975 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.661 ms/op
                 createUser·p0.90:   7.299 ms/op
                 createUser·p0.95:   8.364 ms/op
                 createUser·p0.99:   11.583 ms/op
                 createUser·p0.999:  28.083 ms/op
                 createUser·p0.9999: 35.038 ms/op
                 createUser·p1.00:   35.717 ms/op

Iteration   3: 12:21:06.716 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.721 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.721 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.721 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.721 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.724 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.724 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:06.725 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.741 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4853&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831605740&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.741 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.741 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4853&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831605740&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.742 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.742 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.743 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.743 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.744 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.745 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.787 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.789 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.789 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.790 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.791 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.791 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.791 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.798 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.798 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:08.800 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
5.774 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   11.112 ms/op
                 createUser·p0.999:  30.908 ms/op
                 createUser·p0.9999: 34.956 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163747
  mean =      5.861 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 32152 
    [ 5.000,  7.500) = 119309 
    [ 7.500, 10.000) = 9235 
    [10.000, 12.500) = 2156 
    [12.500, 15.000) = 508 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 85 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     26.911 ms/op
     p(99.9900) =     34.775 ms/op
     p(99.9990) =     35.741 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 12:21:10.908 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:21:10.913 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:10.992 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:10.994 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.019 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.019 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.077 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.077 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.077 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.084 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.084 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.095 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.095 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.099 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.102 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.102 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.339 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:21:11.386 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:21:11.406 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:21:11.552 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.562 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.563 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.799 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:21:11.831 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.832 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.832 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.833 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:11.881 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.008 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.237 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.239 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.252 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.259 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.262 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.305 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.357 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.360 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5142&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831672294&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.360 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5142&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831672294&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.361 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.470 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.473 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5142&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831672294&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.475 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:21:12.487 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
18.502 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 6.381 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.790 ±(99.9%) 0.023 ms/op
Iteration   1: 5.758 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.351 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.299 ms/op
                 existUser·p0.95:   8.487 ms/op
                 existUser·p0.99:   11.616 ms/op
                 existUser·p0.999:  20.414 ms/op
                 existUser·p0.9999: 28.042 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   2: 5.720 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   7.274 ms/op
                 existUser·p0.95:   8.880 ms/op
                 existUser·p0.99:   13.058 ms/op
                 existUser·p0.999:  26.940 ms/op
                 existUser·p0.9999: 32.087 ms/op
                 existUser·p1.00:   32.834 ms/op

Iteration   3: 12:22:13.283 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.287 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.287 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.288 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.288 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.290 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.293 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:13.296 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.306 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5142&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831672294&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.306 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.306 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5142&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831672294&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.306 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.306 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.309 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.310 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.310 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.311 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.325 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.333 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.333 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.334 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.334 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.335 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.335 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.335 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.336 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.338 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.338 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.338 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.348 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.348 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:15.352 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-32] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3fe130d4, dubbo version: 3.1.0, current host: 10.1.54.1
5.635 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.111 ms/op
                 existUser·p0.95:   8.126 ms/op
                 existUser·p0.99:   11.196 ms/op
                 existUser·p0.999:  28.811 ms/op
                 existUser·p0.9999: 38.163 ms/op
                 existUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168278
  mean =      5.704 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 52077 
    [ 5.000,  7.500) = 101916 
    [ 7.500, 10.000) = 10363 
    [10.000, 12.500) = 2442 
    [12.500, 15.000) = 804 
    [15.000, 17.500) = 353 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     24.567 ms/op
     p(99.9900) =     37.105 ms/op
     p(99.9990) =     38.425 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 12:22:17.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.451 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.528 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.530 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.553 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.554 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.617 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.618 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.618 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.624 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.625 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.635 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.636 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.639 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.643 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.643 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2d25d6a6, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:17.866 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:22:17.926 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:22:17.952 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:22:18.124 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.134 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.140 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.431 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:22:18.460 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.461 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.462 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.463 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.506 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.627 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.847 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.849 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.860 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.867 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.870 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.915 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.959 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.962 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5431&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831738903&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.962 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5431&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831738903&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:18.963 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:19.056 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:22:19.059 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5431&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831738903&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:22:19.060 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:22:19.069 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
18.911 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 7.519 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.814 ±(99.9%) 0.021 ms/op
Iteration   1: 5.798 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   7.209 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.928 ms/op
                 getUser·p0.999:  17.629 ms/op
                 getUser·p0.9999: 31.275 ms/op
                 getUser·p1.00:   32.539 ms/op

Iteration   2: 5.925 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.888 ms/op
                 getUser·p0.50:   5.521 ms/op
                 getUser·p0.90:   7.537 ms/op
                 getUser·p0.95:   8.765 ms/op
                 getUser·p0.99:   12.228 ms/op
                 getUser·p0.999:  30.180 ms/op
                 getUser·p0.9999: 34.853 ms/op
                 getUser·p1.00:   35.324 ms/op

Iteration   3: 12:23:19.767 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.772 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.784 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.784 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.784 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.789 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.789 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:19.790 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.801 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5431&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831738903&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.802 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.802 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5431&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831738903&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.803 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.803 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.804 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.804 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.804 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.805 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.822 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.827 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.828 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.828 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.828 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.829 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.830 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.831 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.832 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.833 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.834 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.834 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.835 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.836 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:21.837 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2d25d6a6, dubbo version: 3.1.0, current host: 10.1.54.1
5.929 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   5.521 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   12.693 ms/op
                 getUser·p0.999:  28.543 ms/op
                 getUser·p0.9999: 31.741 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163048
  mean =      5.884 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 41459 
    [ 5.000,  7.500) = 105664 
    [ 7.500, 10.000) = 11731 
    [10.000, 12.500) = 2585 
    [12.500, 15.000) = 1080 
    [15.000, 17.500) = 276 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     12.419 ms/op
     p(99.9000) =     23.072 ms/op
     p(99.9900) =     32.725 ms/op
     p(99.9990) =     35.159 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12:23:24.824 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.828 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.890 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.892 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.918 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.919 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.975 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.975 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.975 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.981 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.981 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.991 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.992 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.995 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.999 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.54.1
12:23:24.999 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@356efe27, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.218 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:23:25.266 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:23:25.287 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:23:25.435 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.446 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.446 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.677 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:23:25.708 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.708 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.708 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.709 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.762 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:25.896 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.104 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.106 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.117 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.124 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.127 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.178 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.281 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.286 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5717&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831806160&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.287 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5717&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831806160&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.289 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.416 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.418 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5717&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831806160&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.54.1
12:23:26.431 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.54.1
21.492 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 8.469 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 7.155 ±(99.9%) 0.034 ms/op
Iteration   1: 6.901 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.146 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.978 ms/op
                 listUser·p0.99:   13.036 ms/op
                 listUser·p0.999:  26.072 ms/op
                 listUser·p0.9999: 32.901 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 6.919 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.277 ms/op
                 listUser·p0.50:   6.570 ms/op
                 listUser·p0.90:   8.380 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   13.140 ms/op
                 listUser·p0.999:  30.651 ms/op
                 listUser·p0.9999: 32.334 ms/op
                 listUser·p1.00:   32.604 ms/op

Iteration   3: 12:24:27.143 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.150 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.150 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.151 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.151 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.153 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.155 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:27.156 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.54.1:20881, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.173 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.54.1:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5717&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831806160&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.173 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.174 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.54.1&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5717&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1686831806160&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.174 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.174 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.175 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.178 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.178 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.180 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.206 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.208 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.208 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.208 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.209 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.209 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.209 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.209 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.210 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.212 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.213 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.213 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.215 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.215 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.54.1
12:24:29.222 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@356efe27, dubbo version: 3.1.0, current host: 10.1.54.1
6.911 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   6.496 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  27.056 ms/op
                 listUser·p0.9999: 30.650 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138857
  mean =      6.910 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 1915 
    [ 5.000,  7.500) = 109799 
    [ 7.500, 10.000) = 20940 
    [10.000, 12.500) = 4312 
    [12.500, 15.000) = 1263 
    [15.000, 17.500) = 292 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 83 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      6.529 ms/op
     p(90.0000) =      8.471 ms/op
     p(95.0000) =      9.765 ms/op
     p(99.0000) =     13.107 ms/op
     p(99.9000) =     28.283 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     33.806 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.467 ± 3.082  ops/ms
ClientPb.existUser                       thrpt       3   5.802 ± 2.383  ops/ms
ClientPb.getUser                         thrpt       3   5.464 ± 0.410  ops/ms
ClientPb.listUser                        thrpt       3   4.695 ± 0.071  ops/ms
ClientPb.createUser                       avgt       3   5.859 ± 1.468   ms/op
ClientPb.existUser                        avgt       3   5.431 ± 0.920   ms/op
ClientPb.getUser                          avgt       3   5.759 ± 1.197   ms/op
ClientPb.listUser                         avgt       3   6.837 ± 1.545   ms/op
ClientPb.createUser                     sample  163747   5.861 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.160           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.289           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.911           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.775           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  168278   5.704 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.209           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.536           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.141           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.105           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.470           ms/op
ClientPb.getUser                        sample  163048   5.884 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.489           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.684           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.419           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.072           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.725           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.324           ms/op
ClientPb.listUser                       sample  138857   6.910 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.107           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.283           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.883           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
```
