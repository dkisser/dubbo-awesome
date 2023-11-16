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
[INFO] dubbo-hessianlite-client                                           [jar]
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
[INFO] -------------< org.apache.dubbo:dubbo-hessianlite-client >--------------
[INFO] Building dubbo-hessianlite-client 1.0-SNAPSHOT                     [4/4]
[INFO]   from ../dubbo-hessianlite-client/pom.xml
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
[INFO] Copying protobuf-java-3.24.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/protobuf-java-3.24.3.jar
[INFO] Copying protobuf-java-util-3.24.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/protobuf-java-util-3.24.3.jar
[INFO] Copying jsr305-3.0.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jsr305-3.0.2.jar
[INFO] Copying gson-2.10.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/gson-2.10.1.jar
[INFO] Copying error_prone_annotations-2.18.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/error_prone_annotations-2.18.0.jar
[INFO] Copying guava-32.0.1-jre.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/guava-32.0.1-jre.jar
[INFO] Copying failureaccess-1.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/failureaccess-1.0.1.jar
[INFO] Copying listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
[INFO] Copying checker-qual-3.33.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/checker-qual-3.33.0.jar
[INFO] Copying j2objc-annotations-2.8.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/j2objc-annotations-2.8.jar
[INFO] Copying grpc-netty-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-netty-1.58.0.jar
[INFO] Copying grpc-core-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-core-1.58.0.jar
[INFO] Copying annotations-4.1.1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/annotations-4.1.1.4.jar
[INFO] Copying animal-sniffer-annotations-1.23.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/animal-sniffer-annotations-1.23.jar
[INFO] Copying grpc-context-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-context-1.58.0.jar
[INFO] Copying grpc-util-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-util-1.58.0.jar
[INFO] Copying netty-codec-http2-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-http2-4.1.97.Final.jar
[INFO] Copying netty-common-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-common-4.1.97.Final.jar
[INFO] Copying netty-buffer-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-buffer-4.1.97.Final.jar
[INFO] Copying netty-transport-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-transport-4.1.97.Final.jar
[INFO] Copying netty-resolver-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-resolver-4.1.97.Final.jar
[INFO] Copying netty-codec-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-4.1.97.Final.jar
[INFO] Copying netty-handler-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-handler-4.1.97.Final.jar
[INFO] Copying netty-codec-http-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-http-4.1.97.Final.jar
[INFO] Copying netty-handler-proxy-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-handler-proxy-4.1.97.Final.jar
[INFO] Copying netty-codec-socks-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-socks-4.1.97.Final.jar
[INFO] Copying perfmark-api-0.26.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/perfmark-api-0.26.0.jar
[INFO] Copying netty-transport-native-unix-common-4.1.97.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-transport-native-unix-common-4.1.97.Final.jar
[INFO] Copying grpc-netty-shaded-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-netty-shaded-1.58.0.jar
[INFO] Copying grpc-protobuf-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-protobuf-1.58.0.jar
[INFO] Copying grpc-api-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-api-1.58.0.jar
[INFO] Copying proto-google-common-protos-2.22.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/proto-google-common-protos-2.22.0.jar
[INFO] Copying grpc-protobuf-lite-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-protobuf-lite-1.58.0.jar
[INFO] Copying grpc-stub-1.58.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-stub-1.58.0.jar
[INFO] Copying jmh-core-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jmh-core-1.21.jar
[INFO] Copying jopt-simple-4.6.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jopt-simple-4.6.jar
[INFO] Copying commons-math3-3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/commons-math3-3.2.jar
[INFO] Copying jmh-generator-annprocess-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jmh-generator-annprocess-1.21.jar
[INFO] Copying dubbo-3.2.7.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar
[INFO] Copying spring-context-5.3.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-context-5.3.25.jar
[INFO] Copying spring-aop-5.3.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-aop-5.3.25.jar
[INFO] Copying spring-beans-5.3.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-beans-5.3.25.jar
[INFO] Copying spring-core-5.3.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-core-5.3.25.jar
[INFO] Copying spring-jcl-5.3.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-jcl-5.3.25.jar
[INFO] Copying spring-expression-5.3.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-expression-5.3.25.jar
[INFO] Copying spring-context-support-1.0.11.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-context-support-1.0.11.jar
[INFO] Copying javassist-3.29.2-GA.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/javassist-3.29.2-GA.jar
[INFO] Copying snakeyaml-2.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/snakeyaml-2.2.jar
[INFO] Copying hessian-lite-3.2.13.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/hessian-lite-3.2.13.jar
[INFO] Copying fastjson2-2.0.40.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/fastjson2-2.0.40.jar
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
[INFO] benchmark-base ..................................... SUCCESS [  3.054 s]
[INFO] server-base ........................................ SUCCESS [  0.319 s]
[INFO] client-base ........................................ SUCCESS [  0.681 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  0.432 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.822 s
[INFO] Finished at: 2023-11-16T18:08:21Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-hessianlite-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-hessianlite-client/target/dubbo-hessianlite-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

[Ljava.lang.String;@6d03e736
# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:22.909 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:22.934 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:22.990 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:22.992 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.008 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.009 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.023 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.024 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.064 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.220 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.220 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.232 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.232 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.235 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.236 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.247 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.250 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.252 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.253 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.255 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.255 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1a851aae, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.422 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.447 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.487 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.535 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.537 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.537 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.537 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.565 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.571 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.575 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.616 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.758 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.759 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.759 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.760 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:23.904 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_Throughput(Client_createUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:23.905 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.009 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:54782 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x8006cd74, L:/10.1.0.169:54782 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.046 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.048 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:24.057 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.057 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.061 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.063 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.103 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:24.175 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_Throughput(Client_createUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:24.176 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.188 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2451&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158104098&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.188 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2451&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158104098&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.190 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_Throughput(Client_createUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:24.191 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.200 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.207 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2451&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158104098&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.208 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:24.213 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
2.208 ops/ms
Iteration   1: 18:08:26.297 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.302 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x8006cd74, L:/10.1.0.169:54782 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.303 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:54782 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.310 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.311 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.311 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.311 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.311 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:26.312 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.318 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2451&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158104098&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.318 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2451&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158104098&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.318 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.319 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.319 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.320 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.322 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.322 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.322 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.322 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.323 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.323 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.324 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.325 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:28.326 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1a851aae, dubbo version: 3.2.7, current host: 10.1.0.169
4.858 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.858 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:30.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.086 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.144 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.146 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.165 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.166 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.180 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.181 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.220 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.395 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.396 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.400 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.401 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.404 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.404 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.421 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.425 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.427 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.427 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.429 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.429 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@461df23d, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.584 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.611 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.651 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.698 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.699 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.700 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.700 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.723 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.730 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.733 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.769 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.910 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.911 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.911 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:30.912 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.048 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_Throughput(Client_existUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:31.049 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.139 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:58838 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.145 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xe5373a18, L:/10.1.0.169:58838 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.146 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.173 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.175 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:31.185 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.186 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.191 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.192 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.233 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:31.300 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_Throughput(Client_existUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:31.300 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.312 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2768&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158111229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.312 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2768&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158111229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.314 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_Throughput(Client_existUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:31.315 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.324 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.330 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2768&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158111229&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.331 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:31.336 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
5.365 ops/ms
Iteration   1: 18:08:33.378 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.381 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xe5373a18, L:/10.1.0.169:58838 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.382 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:58838 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.395 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.395 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.395 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.396 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.396 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:33.397 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.466 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2768&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158111229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.466 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2768&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158111229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.466 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.467 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.468 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.469 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.470 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.470 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.471 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.471 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.471 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.471 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.472 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.472 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.472 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.473 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.473 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.473 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.475 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.475 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:35.476 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@461df23d, dubbo version: 3.2.7, current host: 10.1.0.169
11.373 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.373 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:37.146 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.173 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.232 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.234 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.250 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.251 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.263 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.264 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.303 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.458 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.459 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.464 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.464 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.466 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.467 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.488 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.488 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.491 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.493 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.495 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.495 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6524e38c, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.663 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.688 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.726 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.770 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.772 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.772 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.772 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.795 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.802 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.805 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.841 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.975 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.976 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:37.976 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.110 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_Throughput(Client_getUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:38.111 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.197 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:36054 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.205 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x05a02413, L:/10.1.0.169:36054 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.205 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.232 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.233 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:38.242 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.243 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.248 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.249 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.292 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:38.363 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_Throughput(Client_getUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:38.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.375 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2886&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158118287&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.376 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2886&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158118287&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.377 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_Throughput(Client_getUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:38.378 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.388 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.414 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2886&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158118287&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.416 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:38.422 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
4.149 ops/ms
Iteration   1: 18:08:40.486 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.489 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x05a02413, L:/10.1.0.169:36054 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.490 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:36054 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.492 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.493 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.493 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:40.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.499 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2886&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158118287&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.500 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2886&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158118287&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.500 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.500 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.501 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.502 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.503 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.503 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.504 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.504 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.504 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.504 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.504 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.504 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.505 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.505 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.505 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.506 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.507 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.508 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:42.509 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6524e38c, dubbo version: 3.2.7, current host: 10.1.0.169
7.750 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.750 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:44.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.328 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.389 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.390 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.408 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.409 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.423 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.424 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.464 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.638 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.638 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.643 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.644 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.647 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.647 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.669 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.669 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.672 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.675 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.677 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.677 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6e9dabfc, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.845 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.874 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.912 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.958 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.960 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.986 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.993 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:44.997 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.178 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.179 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.179 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.180 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.332 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.refer(ProtocolSecurityWrapper.java:110)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_Throughput(Client_listUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:45.333 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.419 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:36068 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.427 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xf7941141, L:/10.1.0.169:36068 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.427 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.455 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.457 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:45.467 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.468 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.473 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.475 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.516 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:45.587 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_Throughput(Client_listUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:45.588 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.591 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3001&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158125512&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.592 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3001&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158125512&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.597 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_Throughput(Client_listUser_jmhTest.java:71)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:45.597 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.605 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.615 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3001&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158125512&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.616 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:45.620 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
1.989 ops/ms
Iteration   1: 18:08:47.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.706 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xf7941141, L:/10.1.0.169:36068 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.707 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:36068 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.708 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.708 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.708 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.709 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.709 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:47.710 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.715 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3001&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158125512&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.716 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3001&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158125512&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.716 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.717 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.717 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.718 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.719 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.722 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.722 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.723 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.724 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:49.725 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-32] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6e9dabfc, dubbo version: 3.2.7, current host: 10.1.0.169
3.954 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.954 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:51.506 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.533 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.592 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.594 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.612 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.625 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.626 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.664 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.830 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.831 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.835 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.836 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.839 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.839 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.862 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.864 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.866 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.867 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.868 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:51.869 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3875d2e9, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.040 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.068 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.106 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.150 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.152 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.153 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.153 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.176 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.183 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.186 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.222 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.358 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.359 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.359 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.360 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.495 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_AverageTime(Client_createUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:52.496 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.588 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:44902 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.595 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xaf50b285, L:/10.1.0.169:44902 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.596 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.625 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.627 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:52.638 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.639 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.643 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.644 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.691 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:52.743 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_AverageTime(Client_createUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:52.744 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.756 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3118&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158132686&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.757 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3118&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158132686&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.760 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_AverageTime(Client_createUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:52.760 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.771 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.780 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3118&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158132686&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.781 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:52.787 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
6.146 ±(99.9%) 0.117 ms/op
Iteration   1: 18:08:54.840 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.842 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xaf50b285, L:/10.1.0.169:44902 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.843 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:44902 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.845 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.846 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.847 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.847 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.848 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:54.848 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.855 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3118&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158132686&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.855 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3118&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158132686&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.855 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.856 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.857 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.858 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.862 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.863 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:56.864 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3875d2e9, dubbo version: 3.2.7, current host: 10.1.0.169
3.461 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.461 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:58.624 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.651 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.710 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.711 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.729 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.730 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.742 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.743 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.779 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.906 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.906 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.918 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.919 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.921 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.922 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.933 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.933 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.936 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.938 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.939 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.940 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:58.941 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1218d94a, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.096 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.123 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.161 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.215 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.215 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.216 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.241 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.248 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.251 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.291 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.433 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.434 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.434 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.434 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.558 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_AverageTime(Client_existUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:59.558 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.664 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:58806 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.668 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x22e4bbaa, L:/10.1.0.169:58806 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.669 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.702 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.704 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:59.715 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.716 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.720 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.721 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.767 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:59.832 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_AverageTime(Client_existUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:59.833 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.847 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3236&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158139761&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.848 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3236&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158139761&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.850 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_AverageTime(Client_existUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:08:59.851 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.861 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.870 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3236&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158139761&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.871 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:08:59.877 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
3.411 ±(99.9%) 0.054 ms/op
Iteration   1: 18:09:01.906 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.909 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x22e4bbaa, L:/10.1.0.169:58806 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.910 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:58806 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.912 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.912 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.913 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.913 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.913 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:01.914 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.920 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3236&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158139761&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.920 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3236&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158139761&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.920 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.921 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.921 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.923 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.923 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.925 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.925 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.925 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.925 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.926 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.927 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.927 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:03.929 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-29] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1218d94a, dubbo version: 3.2.7, current host: 10.1.0.169
2.099 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:05.720 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.744 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.802 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.804 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.822 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.823 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.836 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.837 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:05.876 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.020 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.020 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.025 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.025 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.048 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.050 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.051 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.052 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.053 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1a851aae, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.202 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.232 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.271 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.317 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.319 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.320 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.320 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.343 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.351 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.354 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.392 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.529 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.530 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.530 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.531 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.658 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_AverageTime(Client_getUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:06.659 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.765 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:53528 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xb955074c, L:/10.1.0.169:53528 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.802 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.804 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:06.815 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.816 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.821 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.822 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.868 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:06.932 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_AverageTime(Client_getUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:06.933 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.947 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3417&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158146864&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.948 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3417&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158146864&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.950 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_AverageTime(Client_getUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:06.950 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.962 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.969 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3417&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158146864&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.970 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:06.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
4.774 ±(99.9%) 0.070 ms/op
Iteration   1: 18:09:09.008 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.011 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xb955074c, L:/10.1.0.169:53528 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.012 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:53528 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.015 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.015 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.015 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.016 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.016 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:09.017 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.022 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3417&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158146864&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.022 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3417&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158146864&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.023 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.023 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.024 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.025 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.026 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.027 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.029 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.030 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.030 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:11.032 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1a851aae, dubbo version: 3.2.7, current host: 10.1.0.169
3.431 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:12.782 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.806 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.865 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.866 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.884 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.885 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.897 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.898 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:12.930 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.052 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.053 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.058 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.059 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.062 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.062 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.072 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.073 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.075 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.084 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.085 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.087 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.087 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7977fecf, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.235 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.260 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.299 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.347 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.349 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.350 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.350 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.377 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.384 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.387 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.425 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.555 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.556 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.556 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.557 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.715 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.refer(ProtocolSecurityWrapper.java:110)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_AverageTime(Client_listUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:13.716 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.802 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:53536 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.811 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x23fdcdee, L:/10.1.0.169:53536 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.812 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.840 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.841 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:13.850 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.851 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.856 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.857 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.897 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:13.971 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_AverageTime(Client_listUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:13.972 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.977 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3535&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158153893&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.977 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3535&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158153893&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.982 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_AverageTime(Client_listUser_jmhTest.java:162)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:13.982 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.990 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.997 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3535&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158153893&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:13.998 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:14.004 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
13.158 ±(99.9%) 0.325 ms/op
Iteration   1: 18:09:16.064 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.066 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x23fdcdee, L:/10.1.0.169:53536 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.067 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:53536 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.069 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.070 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.070 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.071 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.071 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:16.072 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.077 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3535&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158153893&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.078 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3535&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158153893&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.078 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.078 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.079 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.080 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.080 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.081 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.082 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.082 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.082 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.082 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.084 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.084 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:18.085 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7977fecf, dubbo version: 3.2.7, current host: 10.1.0.169
9.225 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.225 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:19.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.881 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.938 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.939 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.958 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.971 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:19.972 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.004 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.129 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.129 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.134 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.135 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.144 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.144 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.154 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.155 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.161 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.161 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.163 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.163 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3875d2e9, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.308 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.336 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.374 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.423 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.424 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.425 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.425 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.448 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.455 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.458 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.496 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.632 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.633 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.633 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.634 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.774 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_SampleTime(Client_createUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:20.775 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.883 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:59514 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.895 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x485ad395, L:/10.1.0.169:59514 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.896 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.938 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.940 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:20.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.958 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.963 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:20.965 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.011 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:21.067 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_SampleTime(Client_createUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:21.068 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.082 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3653&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158161006&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.082 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3653&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158161006&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.085 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest._jmh_tryInit_f_client0_G(Client_createUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_createUser_jmhTest.createUser_SampleTime(Client_createUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:21.085 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.095 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.104 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3653&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158161006&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.105 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:21.111 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
5.698 ±(99.9%) 0.135 ms/op
Iteration   1: 18:09:23.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.337 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x485ad395, L:/10.1.0.169:59514 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.339 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:59514 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.341 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.341 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.341 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.342 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.342 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:23.343 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.348 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3653&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158161006&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.348 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3653&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158161006&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.348 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.349 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.349 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.350 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.351 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.352 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.352 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.352 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.352 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.352 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.353 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.353 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.353 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.354 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.354 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.354 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.356 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.356 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:25.357 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-27] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3875d2e9, dubbo version: 3.2.7, current host: 10.1.0.169
3.297 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   4.122 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  21.272 ms/op
                 createUser·p0.9999: 21.496 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9815
  mean =      3.297 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1565 
    [ 2.500,  5.000) = 7849 
    [ 5.000,  7.500) = 192 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.122 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     21.272 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:27.176 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.201 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.257 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.259 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.277 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.277 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.289 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.290 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.325 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.477 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.478 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.482 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.482 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.492 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.493 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.502 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.503 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.506 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.508 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.508 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.510 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.510 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@bacce0a, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.652 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.677 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.714 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.763 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.764 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.765 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.765 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.788 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.795 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.798 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.840 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.973 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.973 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.974 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:27.974 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.143 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.refer(ProtocolSecurityWrapper.java:110)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_SampleTime(Client_existUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:28.144 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.236 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:50778 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.243 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x1dac5aff, L:/10.1.0.169:50778 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.243 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.272 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.274 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:28.283 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.284 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.289 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.290 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.328 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:28.395 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_SampleTime(Client_existUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:28.396 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.400 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3770&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158168323&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.400 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3770&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158168323&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.404 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest._jmh_tryInit_f_client0_G(Client_existUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_existUser_jmhTest.existUser_SampleTime(Client_existUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:28.405 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.411 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.418 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3770&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158168323&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.419 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:28.424 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
3.043 ±(99.9%) 0.057 ms/op
Iteration   1: 18:09:30.518 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.520 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1dac5aff, L:/10.1.0.169:50778 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.522 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:50778 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.523 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.524 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.524 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.525 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.525 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:30.525 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.530 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3770&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158168323&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.530 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3770&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158168323&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.531 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.531 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.532 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.532 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.533 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.534 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.534 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.534 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.535 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.535 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.535 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.535 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.535 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.536 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.536 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.536 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.538 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.538 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:32.539 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@bacce0a, dubbo version: 3.2.7, current host: 10.1.0.169
1.961 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.687 ms/op
                 existUser·p0.999:  14.195 ms/op
                 existUser·p0.9999: 15.309 ms/op
                 existUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16292
  mean =      1.961 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 274 
    [ 1.250,  2.500) = 14723 
    [ 2.500,  3.750) = 1151 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.687 ms/op
     p(99.9000) =     14.195 ms/op
     p(99.9900) =     15.309 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:34.333 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.355 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.410 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.412 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.428 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.429 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.439 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.479 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.632 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.633 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.637 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.637 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.647 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.648 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.659 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.659 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.662 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.663 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.664 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.665 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.666 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@461df23d, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.836 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.874 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.918 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.919 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.920 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.920 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.946 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.954 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.958 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:34.996 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.131 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.132 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.133 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.133 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.285 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_SampleTime(Client_getUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:35.286 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.386 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:50794 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.397 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x4f76e4e8, L:/10.1.0.169:50794 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.397 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.439 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.441 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:35.450 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.451 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.455 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.456 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.500 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:35.560 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_SampleTime(Client_getUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:35.561 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.574 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3885&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158175495&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.575 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3885&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158175495&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.578 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest._jmh_tryInit_f_client0_G(Client_getUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_getUser_jmhTest.getUser_SampleTime(Client_getUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:35.578 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.590 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.598 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3885&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158175495&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.599 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:35.605 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
4.718 ±(99.9%) 0.105 ms/op
Iteration   1: 18:09:37.748 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.750 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x4f76e4e8, L:/10.1.0.169:50794 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.751 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:50794 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.752 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.752 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.753 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.753 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.753 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:37.754 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.761 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3885&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158175495&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.761 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3885&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158175495&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.761 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.762 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.762 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.763 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.764 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.764 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.766 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.766 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.766 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.767 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.769 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.769 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:39.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@461df23d, dubbo version: 3.2.7, current host: 10.1.0.169
2.941 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   2.806 ms/op
                 getUser·p0.90:   3.758 ms/op
                 getUser·p0.95:   4.237 ms/op
                 getUser·p0.99:   6.565 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 18.034 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11055
  mean =      2.941 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 3850 
    [ 2.500,  3.750) = 6057 
    [ 3.750,  5.000) = 802 
    [ 5.000,  6.250) = 189 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.758 ms/op
     p(95.0000) =      4.237 ms/op
     p(99.0000) =      6.565 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     18.034 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:41.583 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.605 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.663 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.664 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.683 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.684 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.697 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.698 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.734 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.896 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.896 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.901 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.901 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.904 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.904 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.923 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.923 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.926 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.927 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.928 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.929 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:41.930 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6e9dabfc, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.099 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.124 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.163 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.214 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.215 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.216 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.216 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.241 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.248 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.252 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.291 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.426 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.426 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.427 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.427 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.574 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.refer(ProtocolListenerWrapper.java:83)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.refer(ProtocolSecurityWrapper.java:110)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.refer(ProtocolFilterWrapper.java:74)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.refer(ProtocolSerializationWrapper.java:52)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.refer(InvokerCountWrapper.java:50)
	at org.apache.dubbo.rpc.Protocol$Adaptive.refer(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ReferenceConfig.createInvoker(ReferenceConfig.java:620)
	at org.apache.dubbo.config.ReferenceConfig.createProxy(ReferenceConfig.java:466)
	at org.apache.dubbo.config.ReferenceConfig.init(ReferenceConfig.java:353)
	at org.apache.dubbo.config.ReferenceConfig.get(ReferenceConfig.java:238)
	at org.apache.dubbo.config.utils.SimpleReferenceCache.get(SimpleReferenceCache.java:132)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.lambda$referServices$6(DefaultModuleDeployer.java:495)
	at java.util.concurrent.ConcurrentHashMap$ValuesView.forEach(ConcurrentHashMap.java:4705)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.referServices(DefaultModuleDeployer.java:475)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:176)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_SampleTime(Client_listUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:42.575 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.655 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:38222 -> /10.1.0.169:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.662 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.169:8080 from NettyClient 10.1.0.169 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xd3313bb7, L:/10.1.0.169:38222 - R:/10.1.0.169:8080]], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.662 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.169 connect to the server /10.1.0.169:8080, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.687 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.689 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:42.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.705 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.745 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.169, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:42.823 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportLocal(ServiceConfig.java:878)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:754)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_SampleTime(Client_listUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:42.824 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.828 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=4008&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158182741&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.828 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=4008&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158182741&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.832 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.169, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolListenerWrapper.export(ProtocolListenerWrapper.java:73)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
	at org.apache.dubbo.rpc.cluster.filter.ProtocolFilterWrapper.export(ProtocolFilterWrapper.java:61)
	at org.apache.dubbo.rpc.protocol.ProtocolSerializationWrapper.export(ProtocolSerializationWrapper.java:47)
	at org.apache.dubbo.rpc.protocol.InvokerCountWrapper.export(InvokerCountWrapper.java:42)
	at org.apache.dubbo.rpc.Protocol$Adaptive.export(Protocol$Adaptive.java)
	at org.apache.dubbo.config.ServiceConfig.doExportUrl(ServiceConfig.java:861)
	at org.apache.dubbo.config.ServiceConfig.exportRemote(ServiceConfig.java:839)
	at org.apache.dubbo.config.ServiceConfig.exportUrl(ServiceConfig.java:771)
	at org.apache.dubbo.config.ServiceConfig.doExportUrlsFor1Protocol(ServiceConfig.java:554)
	at org.apache.dubbo.config.ServiceConfig.doExportUrls(ServiceConfig.java:536)
	at org.apache.dubbo.config.ServiceConfig.doExport(ServiceConfig.java:498)
	at org.apache.dubbo.config.ServiceConfig.export(ServiceConfig.java:327)
	at org.apache.dubbo.config.ServiceConfigBase.export(ServiceConfigBase.java:421)
	at org.apache.dubbo.config.metadata.ConfigurableMetadataServiceExporter.export(ConfigurableMetadataServiceExporter.java:72)
	at org.apache.dubbo.config.metadata.ExporterDeployListener.onModuleStarted(ExporterDeployListener.java:85)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.exportMetadataService(DefaultApplicationDeployer.java:1177)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.prepareApplicationInstance(DefaultApplicationDeployer.java:744)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.checkState(DefaultApplicationDeployer.java:1068)
	at org.apache.dubbo.config.deploy.DefaultApplicationDeployer.notifyModuleChanged(DefaultApplicationDeployer.java:1056)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.onModuleStarted(DefaultModuleDeployer.java:332)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.startSync(DefaultModuleDeployer.java:181)
	at org.apache.dubbo.config.deploy.DefaultModuleDeployer.start(DefaultModuleDeployer.java:148)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onContextRefreshedEvent(DubboDeployApplicationListener.java:155)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:141)
	at org.apache.dubbo.config.spring.context.DubboDeployApplicationListener.onApplicationEvent(DubboDeployApplicationListener.java:52)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.doInvokeListener(SimpleApplicationEventMulticaster.java:176)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.invokeListener(SimpleApplicationEventMulticaster.java:169)
	at org.springframework.context.event.SimpleApplicationEventMulticaster.multicastEvent(SimpleApplicationEventMulticaster.java:143)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:421)
	at org.springframework.context.support.AbstractApplicationContext.publishEvent(AbstractApplicationContext.java:378)
	at org.springframework.context.support.AbstractApplicationContext.finishRefresh(AbstractApplicationContext.java:938)
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:586)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:144)
	at org.springframework.context.support.ClassPathXmlApplicationContext.<init>(ClassPathXmlApplicationContext.java:85)
	at org.apache.dubbo.benchmark.Client.<init>(Client.java:36)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B1.<init>(Client_jmhType_B1.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B2.<init>(Client_jmhType_B2.java:3)
	at org.apache.dubbo.benchmark.generated.Client_jmhType_B3.<init>(Client_jmhType_B3.java:2)
	at org.apache.dubbo.benchmark.generated.Client_jmhType.<init>(Client_jmhType.java:2)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest._jmh_tryInit_f_client0_G(Client_listUser_jmhTest.java:437)
	at org.apache.dubbo.benchmark.generated.Client_listUser_jmhTest.listUser_SampleTime(Client_listUser_jmhTest.java:253)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:498)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:453)
	at org.openjdk.jmh.runner.BenchmarkHandler$BenchmarkTask.call(BenchmarkHandler.java:437)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:511)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1149)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:624)
	at java.lang.Thread.run(Thread.java:750)
Caused by: java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:141)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:600)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:579)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.runTask(AbstractEventExecutor.java:174)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:167)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:470)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:569)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:997)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	... 1 common frames omitted
18:09:42.833 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.840 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.846 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=4008&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158182741&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.847 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:42.851 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.169
13.952 ±(99.9%) 0.435 ms/op
Iteration   1: 18:09:45.021 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.023 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xd3313bb7, L:/10.1.0.169:38222 - R:/10.1.0.169:8080], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.024 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.169:38222 -> /10.1.0.169:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.026 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.026 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.027 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.027 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.028 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:45.028 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.169:20880, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.034 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.169:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=4008&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158182741&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.034 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.169&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=4008&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700158182741&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.034 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.035 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.035 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.036 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.037 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.041 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.041 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.169
18:09:47.042 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-29] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6e9dabfc, dubbo version: 3.2.7, current host: 10.1.0.169
8.660 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   8.188 ms/op
                 listUser·p0.90:   11.321 ms/op
                 listUser·p0.95:   12.608 ms/op
                 listUser·p0.99:   16.566 ms/op
                 listUser·p0.999:  21.076 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3688
  mean =      8.660 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 64 
    [ 5.000,  7.500) = 1164 
    [ 7.500, 10.000) = 1572 
    [10.000, 12.500) = 694 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.417 ms/op
     p(50.0000) =      8.188 ms/op
     p(90.0000) =     11.321 ms/op
     p(95.0000) =     12.608 ms/op
     p(99.0000) =     16.566 ms/op
     p(99.9000) =     21.076 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.858          ops/ms
Client.existUser                       thrpt         11.373          ops/ms
Client.getUser                         thrpt          7.750          ops/ms
Client.listUser                        thrpt          3.954          ops/ms
Client.createUser                       avgt          3.461           ms/op
Client.existUser                        avgt          2.099           ms/op
Client.getUser                          avgt          3.431           ms/op
Client.listUser                         avgt          9.225           ms/op
Client.createUser                     sample   9815   3.297 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          1.114           ms/op
Client.createUser:createUser·p0.50    sample          2.945           ms/op
Client.createUser:createUser·p0.90    sample          4.122           ms/op
Client.createUser:createUser·p0.95    sample          4.628           ms/op
Client.createUser:createUser·p0.99    sample         11.567           ms/op
Client.createUser:createUser·p0.999   sample         21.272           ms/op
Client.createUser:createUser·p0.9999  sample         21.496           ms/op
Client.createUser:createUser·p1.00    sample         21.496           ms/op
Client.existUser                      sample  16292   1.961 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.523           ms/op
Client.existUser:existUser·p0.50      sample          1.876           ms/op
Client.existUser:existUser·p0.90      sample          2.458           ms/op
Client.existUser:existUser·p0.95      sample          2.609           ms/op
Client.existUser:existUser·p0.99      sample          3.687           ms/op
Client.existUser:existUser·p0.999     sample         14.195           ms/op
Client.existUser:existUser·p0.9999    sample         15.309           ms/op
Client.existUser:existUser·p1.00      sample         15.319           ms/op
Client.getUser                        sample  11055   2.941 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          0.766           ms/op
Client.getUser:getUser·p0.50          sample          2.806           ms/op
Client.getUser:getUser·p0.90          sample          3.758           ms/op
Client.getUser:getUser·p0.95          sample          4.237           ms/op
Client.getUser:getUser·p0.99          sample          6.565           ms/op
Client.getUser:getUser·p0.999         sample         13.746           ms/op
Client.getUser:getUser·p0.9999        sample         18.034           ms/op
Client.getUser:getUser·p1.00          sample         18.055           ms/op
Client.listUser                       sample   3688   8.660 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.417           ms/op
Client.listUser:listUser·p0.50        sample          8.188           ms/op
Client.listUser:listUser·p0.90        sample         11.321           ms/op
Client.listUser:listUser·p0.95        sample         12.608           ms/op
Client.listUser:listUser·p0.99        sample         16.566           ms/op
Client.listUser:listUser·p0.999       sample         21.076           ms/op
Client.listUser:listUser·p0.9999      sample         21.889           ms/op
Client.listUser:listUser·p1.00        sample         21.889           ms/op
```
