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
[INFO] benchmark-base ..................................... SUCCESS [  4.595 s]
[INFO] server-base ........................................ SUCCESS [  0.607 s]
[INFO] client-base ........................................ SUCCESS [  0.945 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.499 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  7.082 s
[INFO] Finished at: 2023-04-03T12:10:52Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-triple-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 12:10:54.422 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.427 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.518 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.521 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.542 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.544 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.595 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.596 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.596 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.601 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.601 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.616 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.616 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.621 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.623 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.623 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@27bb94d1, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:54.837 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:10:54.882 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:10:54.899 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:10:55.076 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.083 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.282 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:10:55.298 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.299 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.299 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.299 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.320 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.418 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.621 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.624 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.636 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.645 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.648 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.694 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.801 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.809 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2081&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523855682&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.810 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2081&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523855682&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.811 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.911 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.913 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2081&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523855682&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.914 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:10:55.920 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
1.378 ops/ms
# Warmup Iteration   2: 3.239 ops/ms
# Warmup Iteration   3: 7.112 ops/ms
Iteration   1: 7.157 ops/ms
Iteration   2: 7.645 ops/ms
Iteration   3: 12:11:56.089 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.094 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.094 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.095 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.095 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.096 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.097 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:56.098 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.108 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2081&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523855682&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.109 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.110 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2081&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523855682&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.110 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.110 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.111 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.111 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.111 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.113 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.135 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.136 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.137 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.138 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.138 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.138 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.142 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.142 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:11:58.143 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-16] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@27bb94d1, dubbo version: 3.1.0, current host: 10.1.0.59
7.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.527 ±(99.9%) 5.963 ops/ms [Average]
  (min, avg, max) = (7.157, 7.527, 7.778), stdev = 0.327
  CI (99.9%): [1.564, 13.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:00.126 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.130 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.181 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.183 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.205 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.205 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.257 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.257 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.257 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.262 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.262 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.270 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.271 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.273 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.276 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.277 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.472 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:00.514 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:00.531 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:00.677 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.685 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.686 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.882 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:00.896 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.897 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.897 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.898 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:00.930 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.040 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.231 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.233 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.244 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.251 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.254 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.325 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.391 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.393 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523921315&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.395 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523921315&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.397 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.517 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.518 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523921315&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.519 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:12:01.534 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
2.081 ops/ms
# Warmup Iteration   2: 6.644 ops/ms
# Warmup Iteration   3: 8.100 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.592 ops/ms
Iteration   3: 12:13:01.657 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.661 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.662 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.662 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.662 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.664 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.664 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:01.665 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.682 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523921315&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.682 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.683 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2586&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523921315&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.683 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.683 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.684 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.684 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.684 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.685 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.696 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.699 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.700 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.701 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.704 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.706 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.714 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.714 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.714 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.715 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.715 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.715 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.716 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.717 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:03.719 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-31] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@217f5b60, dubbo version: 3.1.0, current host: 10.1.0.59
8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.444 ±(99.9%) 4.020 ops/ms [Average]
  (min, avg, max) = (8.191, 8.444, 8.592), stdev = 0.220
  CI (99.9%): [4.424, 12.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 12:13:06.548 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.551 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.604 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.606 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.628 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.629 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.682 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.682 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.682 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.687 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.687 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.696 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.696 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.699 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.703 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.703 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:06.941 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:13:07.013 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:13:07.042 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:13:07.196 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.211 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.212 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.409 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:13:07.426 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.427 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.427 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.427 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.450 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.567 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.753 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.755 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.765 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.772 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.775 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.807 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.842 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.843 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523987798&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.844 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523987798&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.845 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.933 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.934 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523987798&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.935 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:13:07.946 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
2.000 ops/ms
# Warmup Iteration   2: 5.712 ops/ms
# Warmup Iteration   3: 7.380 ops/ms
Iteration   1: 7.532 ops/ms
Iteration   2: 8.245 ops/ms
Iteration   3: 12:14:08.079 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.086 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.086 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.086 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.087 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.088 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.088 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:08.094 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.102 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523987798&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.103 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.103 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2888&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680523987798&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.103 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.104 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.105 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.106 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.107 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.110 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.125 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.127 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.128 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.130 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.130 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.130 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.130 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.131 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.131 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.131 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.131 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.133 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.133 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:10.136 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-8] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.59
8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.975 ±(99.9%) 7.061 ops/ms [Average]
  (min, avg, max) = (7.532, 7.975, 8.245), stdev = 0.387
  CI (99.9%): [0.915, 15.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 12:14:12.058 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.063 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.128 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.129 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.150 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.151 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.209 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.210 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.210 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.214 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.215 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.223 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.223 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.226 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.229 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.229 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.427 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:14:12.471 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:14:12.491 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:14:12.609 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.618 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.619 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.813 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:14:12.833 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.834 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.834 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.835 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.872 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:12.982 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.175 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.177 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.188 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.194 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.197 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.231 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.266 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.268 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3185&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524053222&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.269 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3185&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524053222&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.269 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.357 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.359 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3185&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524053222&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.365 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:14:13.372 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
2.187 ops/ms
# Warmup Iteration   2: 4.987 ops/ms
# Warmup Iteration   3: 6.329 ops/ms
Iteration   1: 6.550 ops/ms
Iteration   2: 6.730 ops/ms
Iteration   3: 12:15:13.517 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.526 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.526 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.526 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.526 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.528 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.528 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:13.530 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.540 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3185&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524053222&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.542 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.542 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3185&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524053222&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.542 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.542 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.543 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.543 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.544 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.545 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.565 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.567 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.568 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.568 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.568 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.568 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.569 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.569 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.569 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.570 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.570 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.570 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.571 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.572 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:15.573 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-28] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.59
6.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.622 ±(99.9%) 1.740 ops/ms [Average]
  (min, avg, max) = (6.550, 6.622, 6.730), stdev = 0.095
  CI (99.9%): [4.882, 8.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12:15:17.515 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.519 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.589 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.590 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.611 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.611 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.661 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.662 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.662 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.668 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.668 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.677 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.677 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.680 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.683 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.683 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:17.883 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:15:17.955 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:15:17.987 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:15:18.146 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.154 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.154 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.359 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:15:18.376 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.376 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.377 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.377 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.416 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.520 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.702 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.704 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.714 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.721 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.723 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.784 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.849 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.852 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3489&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524118771&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.853 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3489&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524118771&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.856 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.969 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.971 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3489&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524118771&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.972 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:15:18.982 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
12.087 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.932 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.009 ms/op
Iteration   1: 4.055 ±(99.9%) 0.010 ms/op
Iteration   2: 3.952 ±(99.9%) 0.014 ms/op
Iteration   3: 12:16:19.122 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.129 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.129 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.130 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.130 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.132 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.132 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:19.133 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.149 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3489&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524118771&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.149 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.149 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3489&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524118771&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.150 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.150 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.151 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.151 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.151 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.152 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.171 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.172 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.172 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.173 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.174 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.174 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.174 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.176 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.176 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:21.177 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5d650f1b, dubbo version: 3.1.0, current host: 10.1.0.59
4.013 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.007 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.952, 4.007, 4.055), stdev = 0.052
  CI (99.9%): [3.061, 4.952] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12:16:24.006 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.011 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.066 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.068 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.098 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.099 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.164 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.164 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.165 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.169 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.170 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.178 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.179 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.181 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.184 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.184 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.381 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:16:24.423 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:16:24.441 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:16:24.571 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.580 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.580 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.828 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:16:24.857 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.858 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.858 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.860 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:24.896 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.003 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.181 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.182 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.192 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.199 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.202 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.286 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.344 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.347 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3782&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524185275&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.347 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3782&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524185275&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.348 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.448 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.450 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3782&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524185275&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.451 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:16:25.459 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
12.319 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.004 ms/op
Iteration   1: 3.821 ±(99.9%) 0.004 ms/op
Iteration   2: 3.940 ±(99.9%) 0.005 ms/op
Iteration   3: 12:17:25.639 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.648 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.649 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.649 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.651 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.653 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.653 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:25.654 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.665 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3782&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524185275&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.667 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.667 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3782&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524185275&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.667 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.667 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.668 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.668 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.668 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.669 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.687 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.688 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.688 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.688 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.689 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.689 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.689 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.690 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.690 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.690 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.690 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.691 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.692 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.692 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:27.696 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@68a4d9f9, dubbo version: 3.1.0, current host: 10.1.0.59
3.865 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.876 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (3.821, 3.876, 3.940), stdev = 0.060
  CI (99.9%): [2.780, 4.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12:17:29.580 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.583 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.634 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.636 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.657 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.658 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.711 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.711 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.712 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.718 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.719 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.727 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.727 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.730 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.732 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.733 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:29.931 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:17:29.981 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:17:30.017 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:17:30.154 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.162 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.163 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.372 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:17:30.390 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.390 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.391 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.391 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.416 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.535 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.738 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.740 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.751 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.757 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.760 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.799 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.848 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.850 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4075&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524250786&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.850 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4075&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524250786&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.851 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.931 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.932 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4075&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524250786&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.934 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:17:30.941 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
14.067 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.005 ms/op
Iteration   1: 3.860 ±(99.9%) 0.011 ms/op
Iteration   2: 4.017 ±(99.9%) 0.004 ms/op
Iteration   3: 12:18:31.080 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.088 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.088 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.088 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.089 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.092 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.098 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:31.099 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.112 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4075&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524250786&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.112 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.113 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4075&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524250786&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.113 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.113 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.114 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.114 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.114 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.115 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.122 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.124 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.125 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.125 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.125 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.127 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.127 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.129 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.129 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.129 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.139 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.139 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:33.140 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.59
3.874 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.917 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (3.860, 3.917, 4.017), stdev = 0.086
  CI (99.9%): [2.339, 5.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12:18:35.071 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.074 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.151 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.153 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.178 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.179 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.228 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.229 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.229 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.242 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.243 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.245 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.248 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.248 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.443 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:18:35.482 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:18:35.499 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:18:35.647 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.659 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.660 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.889 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:18:35.904 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.904 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.904 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.905 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:35.927 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.034 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.224 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.225 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.252 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.269 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.277 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.329 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.411 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.414 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4366&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524316313&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.415 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4366&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524316313&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.418 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.508 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.513 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4366&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524316313&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.514 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:18:36.524 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
14.819 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.018 ±(99.9%) 0.009 ms/op
Iteration   1: 4.863 ±(99.9%) 0.006 ms/op
Iteration   2: 4.840 ±(99.9%) 0.006 ms/op
Iteration   3: 12:19:36.659 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.667 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.667 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.667 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.667 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.669 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.671 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:36.677 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.693 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4366&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524316313&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.693 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.694 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4366&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524316313&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.694 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.694 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.695 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.695 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.695 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.696 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.703 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.713 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.714 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.715 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.716 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.716 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.716 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.716 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.717 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.717 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.717 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.718 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.719 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.719 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:38.720 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.59
4.726 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.810 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (4.726, 4.810, 4.863), stdev = 0.073
  CI (99.9%): [3.469, 6.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12:19:41.534 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.538 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.587 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.589 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.610 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.610 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.660 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.660 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.660 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.665 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.665 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.673 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.674 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.676 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.679 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.679 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:41.871 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:19:41.910 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:19:41.930 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:19:42.081 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.088 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.089 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.280 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:19:42.293 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.294 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.294 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.295 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.327 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.438 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.643 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.644 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.662 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.677 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.686 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.777 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.843 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.845 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4719&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524382737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.846 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4719&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524382737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.847 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.949 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.951 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4719&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524382737&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.952 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:19:42.961 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
13.459 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.723 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.019 ms/op
Iteration   1: 4.251 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  24.936 ms/op
                 createUser·p0.9999: 28.983 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   2: 4.115 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.774 ms/op
                 createUser·p0.999:  14.884 ms/op
                 createUser·p0.9999: 29.837 ms/op
                 createUser·p1.00:   31.195 ms/op

Iteration   3: 12:20:43.817 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.821 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.821 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.821 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.821 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.823 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.823 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:43.824 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.844 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4719&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524382737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.844 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.845 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4719&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524382737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.845 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.845 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.846 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.846 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.847 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.848 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.856 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.864 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.867 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.867 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.868 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.869 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.870 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.871 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.871 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.872 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.872 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.872 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.874 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.874 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:45.875 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@317f28be, dubbo version: 3.1.0, current host: 10.1.0.59
4.147 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.207 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  27.787 ms/op
                 createUser·p0.9999: 30.821 ms/op
                 createUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230128
  mean =      4.170 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 307 
    [ 2.500,  5.000) = 209483 
    [ 5.000,  7.500) = 17395 
    [ 7.500, 10.000) = 2039 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 133 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     25.231 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.660 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12:20:48.768 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.773 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.845 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.848 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.873 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.874 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.931 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.932 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.932 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.937 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.937 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.945 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.946 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.949 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.951 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:20:48.952 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.152 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:20:49.191 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:20:49.217 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:20:49.353 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.368 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.369 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.599 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:20:49.628 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.628 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.629 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.631 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.659 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.766 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.953 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.955 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.965 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.979 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:49.982 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.047 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.099 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.101 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5008&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524450029&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.101 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5008&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524450029&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.102 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.217 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.218 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5008&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524450029&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.219 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:20:50.230 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
12.081 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.012 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  20.292 ms/op
                 existUser·p0.9999: 22.966 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.901 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  11.798 ms/op
                 existUser·p0.9999: 24.622 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 12:21:51.038 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.046 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.046 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.047 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.047 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.049 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.051 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:51.052 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.068 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5008&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524450029&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.069 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.069 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5008&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524450029&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.069 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.069 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.070 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.070 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.070 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.071 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.083 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.088 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.089 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.089 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.091 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.093 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.093 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.094 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.095 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.096 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.096 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.096 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.098 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.098 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:53.102 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1c818de1, dubbo version: 3.1.0, current host: 10.1.0.59
3.952 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  27.034 ms/op
                 existUser·p0.9999: 31.549 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245856
  mean =      3.903 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 288 
    [ 2.500,  5.000) = 232136 
    [ 5.000,  7.500) = 11788 
    [ 7.500, 10.000) = 998 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     19.848 ms/op
     p(99.9900) =     30.160 ms/op
     p(99.9990) =     32.496 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12:21:56.017 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.021 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.080 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.082 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.103 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.104 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.155 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.156 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.156 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.160 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.161 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.169 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.169 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.172 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.174 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.175 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.384 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:21:56.438 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:21:56.467 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:21:56.633 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.649 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.649 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.879 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:21:56.901 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.902 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.902 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.903 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:56.934 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.055 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.236 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.238 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.248 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.254 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.257 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.288 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.350 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.352 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5293&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524517280&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.352 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5293&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524517280&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.353 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.453 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.455 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5293&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524517280&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.456 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:21:57.470 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
11.213 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.399 ±(99.9%) 0.017 ms/op
Iteration   1: 4.005 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.878 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  24.445 ms/op
                 getUser·p0.9999: 34.407 ms/op
                 getUser·p1.00:   36.831 ms/op

Iteration   2: 4.035 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  12.803 ms/op
                 getUser·p0.9999: 29.461 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 12:22:58.063 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.070 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.070 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.070 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.071 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.073 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.078 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:22:58.079 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.093 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5293&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524517280&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.093 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.093 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5293&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524517280&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.093 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.093 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.094 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.094 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.095 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.096 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.112 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.115 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.116 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.116 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.116 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.119 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.119 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.119 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.120 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.120 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:00.122 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@25fe54e1, dubbo version: 3.1.0, current host: 10.1.0.59
4.095 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  27.130 ms/op
                 getUser·p0.9999: 30.245 ms/op
                 getUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237110
  mean =      4.045 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 222571 
    [ 5.000,  7.500) = 11396 
    [ 7.500, 10.000) = 2468 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 111 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     24.507 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     36.206 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12:23:03.036 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.040 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.091 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.093 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.118 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.119 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.170 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.170 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.170 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.175 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.176 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.184 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.184 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.187 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.189 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.190 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3dc37d07, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.392 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:23:03.462 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:23:03.486 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:23:03.650 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.665 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.669 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.869 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:23:03.886 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.886 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.887 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.887 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:03.907 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.013 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.225 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.226 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.238 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.244 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.247 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.284 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.321 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.351 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5579&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524584271&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.351 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5579&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524584271&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.352 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.439 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.441 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5579&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524584271&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.442 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.59
12:23:04.450 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.59
13.987 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.352 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.018 ms/op
Iteration   1: 4.815 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  26.182 ms/op
                 listUser·p0.9999: 28.967 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   2: 4.717 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.432 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.374 ms/op
                 listUser·p0.999:  18.102 ms/op
                 listUser·p0.9999: 23.928 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 12:24:05.365 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.373 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.374 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.374 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.374 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.379 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.379 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:05.380 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.59:20881, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.391 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5579&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524584271&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.392 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.392 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.59&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5579&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1680524584271&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.392 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.393 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.394 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.394 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.394 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.395 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.417 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.419 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.420 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.420 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.420 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.421 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.421 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.422 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.423 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.59
12:24:07.425 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3dc37d07, dubbo version: 3.1.0, current host: 10.1.0.59
4.871 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  19.836 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199821
  mean =      4.800 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 156457 
    [ 5.000,  7.500) = 38078 
    [ 7.500, 10.000) = 4216 
    [10.000, 12.500) = 542 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.999 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.406 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     20.781 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     29.394 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.527 ± 5.963  ops/ms
ClientPb.existUser                       thrpt       3   8.444 ± 4.020  ops/ms
ClientPb.getUser                         thrpt       3   7.975 ± 7.061  ops/ms
ClientPb.listUser                        thrpt       3   6.622 ± 1.740  ops/ms
ClientPb.createUser                       avgt       3   4.007 ± 0.946   ms/op
ClientPb.existUser                        avgt       3   3.876 ± 1.096   ms/op
ClientPb.getUser                          avgt       3   3.917 ± 1.578   ms/op
ClientPb.listUser                         avgt       3   4.810 ± 1.341   ms/op
ClientPb.createUser                     sample  230128   4.170 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.790           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.864           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.231           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.310           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.818           ms/op
ClientPb.existUser                      sample  245856   3.903 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.848           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.160           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.571           ms/op
ClientPb.getUser                        sample  237110   4.045 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.704           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.507           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.047           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.831           ms/op
ClientPb.listUser                       sample  199821   4.800 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.999           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.406           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.781           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.606           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.245           ms/op
```
