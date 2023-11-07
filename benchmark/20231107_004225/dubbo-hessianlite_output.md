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
[INFO] benchmark-base ..................................... SUCCESS [  3.584 s]
[INFO] server-base ........................................ SUCCESS [  0.343 s]
[INFO] client-base ........................................ SUCCESS [  0.682 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  0.442 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.434 s
[INFO] Finished at: 2023-11-07T00:29:22Z
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
# Warmup Iteration   1: 00:29:23.931 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:23.969 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.031 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.033 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.053 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.054 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.072 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.073 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.122 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.289 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.289 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.296 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.297 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.301 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.302 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.318 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.319 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.321 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.326 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.328 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.330 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.331 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.514 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.548 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.606 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.675 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.681 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.683 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.684 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.711 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.725 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.731 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.776 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.958 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:24.958 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.118 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.refer(ProtocolSecurityWrapper.java:110)
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
00:29:25.119 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.243 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:60240 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.245 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xa657a48f, L:/10.1.0.60:60240 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.257 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.293 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.295 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:29:25.304 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.305 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.317 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.318 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.380 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:29:25.453 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
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
00:29:25.454 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.456 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2190&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316965376&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.457 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2190&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316965376&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.474 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
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
00:29:25.474 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.483 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.493 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2190&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316965376&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.494 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:25.502 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
1.448 ops/ms
Iteration   1: 00:29:27.566 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.571 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xa657a48f, L:/10.1.0.60:60240 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.572 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:60240 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.584 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.584 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.584 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.585 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.585 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:27.585 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.608 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2190&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316965376&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.608 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2190&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316965376&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.609 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.609 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.610 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.611 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.614 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.614 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.615 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.615 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.615 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.616 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.616 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.616 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.618 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.618 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:29.619 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.60
4.024 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.024 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 00:29:31.465 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.505 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.566 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.568 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.584 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.585 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.601 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.602 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.644 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.801 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.801 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.808 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.808 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.814 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.815 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.846 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.846 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.849 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.854 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.855 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.858 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:31.858 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.054 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.084 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.122 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.190 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.197 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.199 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.200 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.227 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.233 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.239 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.289 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.460 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.461 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.462 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.463 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.608 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:32.608 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.738 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xc7c78e58, L:/10.1.0.60:56066 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.738 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.741 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:56066 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.767 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.768 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:29:32.783 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.784 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.788 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.793 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.840 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:29:32.893 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:32.893 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.910 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2486&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316972833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.910 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2486&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316972833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.929 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:32.930 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.940 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.949 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2486&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316972833&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.950 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:32.956 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
5.100 ops/ms
Iteration   1: 00:29:34.992 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:34.994 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xc7c78e58, L:/10.1.0.60:56066 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:34.995 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:56066 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:35.005 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:35.005 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:35.005 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:35.006 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:35.006 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:35.007 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.032 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2486&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316972833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.032 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2486&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316972833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.033 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.033 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.034 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.035 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.035 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.036 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.037 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.037 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.037 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.037 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.038 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.038 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.041 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.041 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:37.045 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-18] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.60
12.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.549 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 00:29:38.861 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.888 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.947 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.948 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.965 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.966 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.977 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:38.978 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.022 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.208 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.211 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.218 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.219 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.224 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.225 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.242 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.243 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.245 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.250 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.251 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.253 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.253 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2115d783, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.448 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.480 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.519 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.581 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.583 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.584 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.584 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.604 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.621 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.630 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.682 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.864 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.865 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.867 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:39.867 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.000 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:40.001 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.145 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x8dbb94bf, L:/10.1.0.60:49760 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.145 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.149 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:49760 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.176 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.177 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:29:40.194 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.195 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.206 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.207 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.267 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:29:40.314 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:40.314 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.332 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2583&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316980262&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.332 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2583&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316980262&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.349 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:40.350 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.359 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.366 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2583&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316980262&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.366 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:40.371 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
2.908 ops/ms
Iteration   1: 00:29:42.411 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.412 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x8dbb94bf, L:/10.1.0.60:49760 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.419 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:49760 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.429 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.430 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.430 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.430 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.430 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:42.431 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.439 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2583&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316980262&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2583&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316980262&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.441 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.442 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.445 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.445 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.445 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.445 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.448 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.449 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.449 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.451 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.452 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:44.458 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-28] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2115d783, dubbo version: 3.2.7, current host: 10.1.0.60
5.978 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.978 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 00:29:46.261 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.294 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.358 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.360 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.376 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.377 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.388 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.389 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.440 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.616 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.617 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.623 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.623 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.629 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.629 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.637 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.637 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.639 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.641 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.641 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.642 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.643 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.820 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.859 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.920 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.981 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.985 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.985 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:46.985 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.016 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.025 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.031 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.076 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.239 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.241 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.243 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.244 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.418 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:47.419 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.565 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x5dbc5291, L:/10.1.0.60:49770 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.565 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.569 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:49770 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.603 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.605 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:29:47.621 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.622 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.627 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.628 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.688 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:29:47.743 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:47.743 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.745 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2680&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316987680&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.745 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2680&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316987680&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.765 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:47.766 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.775 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.782 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2680&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316987680&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.783 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:47.788 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
1.219 ops/ms
Iteration   1: 00:29:49.911 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.916 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x5dbc5291, L:/10.1.0.60:49770 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.916 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:49770 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.932 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.933 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.933 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.934 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.934 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:49.934 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.956 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2680&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316987680&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.956 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2680&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316987680&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.956 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.957 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.957 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.958 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.959 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.962 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.963 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.964 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.964 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.964 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.964 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.966 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.966 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:51.967 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.60
1.961 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.961 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 00:29:53.765 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.796 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.852 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.853 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.871 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.873 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.893 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.898 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:53.944 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.117 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.118 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.126 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.126 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.132 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.133 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.140 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.140 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.142 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.144 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.144 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.146 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.146 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.332 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.366 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.465 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.467 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.467 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.468 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.488 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.495 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.500 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.546 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.706 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.707 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.709 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.710 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:54.874 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:54.875 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.009 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x6fba9165, L:/10.1.0.60:57532 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.009 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:57532 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.009 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.047 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.049 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:29:55.067 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.068 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.073 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.075 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.138 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:29:55.209 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:55.210 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.212 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2772&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316995129&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.212 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2772&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316995129&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.230 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:29:55.230 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.237 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.244 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2772&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316995129&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.245 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:55.250 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
8.390 ±(99.9%) 0.187 ms/op
Iteration   1: 00:29:57.297 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.299 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x6fba9165, L:/10.1.0.60:57532 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.300 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:57532 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.308 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.308 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.317 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.317 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.317 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:57.318 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.330 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2772&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316995129&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.330 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2772&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699316995129&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.330 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.331 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.331 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.332 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.333 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.334 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.335 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.335 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.335 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.337 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.337 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:29:59.339 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.60
4.646 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.646 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:01.176 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.217 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.279 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.281 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.297 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.298 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.309 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.310 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.344 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.504 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.504 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.511 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.511 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.516 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.516 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.532 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.533 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.536 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.545 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.545 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.549 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.549 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3e2d3332, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.736 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.769 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.880 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.881 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.882 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.882 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.907 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.915 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.917 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:01.964 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.126 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.127 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.127 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.128 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.293 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:02.293 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.421 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x7fba78dc, L:/10.1.0.60:59344 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.426 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:59344 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.457 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:02.475 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.475 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.480 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.482 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.543 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:02.599 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:02.600 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.603 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317002535&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.603 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317002535&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.625 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:02.626 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.633 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.642 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317002535&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.643 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:02.648 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
4.806 ±(99.9%) 0.061 ms/op
Iteration   1: 00:30:04.683 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.685 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x7fba78dc, L:/10.1.0.60:59344 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.686 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:59344 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.697 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.697 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.698 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.698 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.698 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:04.699 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.730 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317002535&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.730 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317002535&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.730 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.731 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.731 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.732 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.733 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.734 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.736 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.736 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.737 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.737 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:06.740 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3e2d3332, dubbo version: 3.2.7, current host: 10.1.0.60
2.257 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.257 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:08.544 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.581 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.637 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.638 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.654 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.655 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.666 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.667 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.704 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.862 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.862 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.868 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.869 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.871 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.871 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.879 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.879 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.881 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.885 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.886 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.900 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:08.901 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.097 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.121 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.159 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.220 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.226 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.228 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.229 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.259 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.270 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.278 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.323 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.473 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.474 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.476 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.476 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.624 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:09.625 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x7fb36533, L:/10.1.0.60:59346 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.765 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.770 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:59346 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.805 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.806 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:09.822 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.823 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.830 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.834 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.897 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:09.957 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:09.958 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.969 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2963&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317009888&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.969 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2963&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317009888&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.985 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:09.986 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:09.995 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:10.005 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2963&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317009888&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:10.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:10.011 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
9.128 ±(99.9%) 0.110 ms/op
Iteration   1: 00:30:12.049 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.051 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x7fb36533, L:/10.1.0.60:59346 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.052 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:59346 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.065 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.066 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.066 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.066 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.066 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:12.067 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.073 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2963&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317009888&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.073 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2963&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317009888&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.073 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.074 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.075 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.076 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.076 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.078 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.078 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.078 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.078 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.078 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.079 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.081 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.081 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:14.084 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.60
3.274 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.274 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:15.947 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:15.985 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.053 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.054 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.071 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.072 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.085 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.086 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.131 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.300 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.309 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.310 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.312 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.313 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.320 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.320 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.322 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.324 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.324 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.326 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.326 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.558 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.589 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.640 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.715 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.744 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.749 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.755 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.815 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.992 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.993 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.993 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:16.993 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.139 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:17.139 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.287 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:42070 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.292 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xdee53c88, L:/10.1.0.60:42070 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.292 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.330 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.332 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:17.347 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.348 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.352 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.353 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.403 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:17.442 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:17.443 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.466 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3060&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317017400&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.466 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3060&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317017400&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.482 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:17.482 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.493 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.502 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3060&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317017400&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.503 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:17.508 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
22.361 ±(99.9%) 0.610 ms/op
Iteration   1: 00:30:19.613 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.618 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xdee53c88, L:/10.1.0.60:42070 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.622 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.622 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.622 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.623 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.623 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:42070 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.623 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:19.624 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.634 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3060&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317017400&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.635 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3060&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317017400&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.635 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.635 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.636 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.637 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.638 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.639 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.642 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.642 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.644 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.644 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.644 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.644 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.644 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.645 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.645 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.645 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.649 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.649 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:21.656 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.60
17.155 ±(99.9%) 0.371 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.155 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:23.500 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.533 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.591 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.592 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.610 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.610 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.634 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.638 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.686 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.862 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.866 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.866 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.868 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.869 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.876 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.877 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.879 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.898 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.899 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.900 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:23.900 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3f27ae26, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.078 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.103 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.135 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.191 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.192 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.193 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.193 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.213 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.222 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.231 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.279 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.432 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.433 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.433 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.433 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.574 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:24.575 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.709 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x6e4c1433, L:/10.1.0.60:46120 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.709 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.716 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:46120 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.753 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.755 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:24.773 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.774 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.782 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.783 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.837 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:24.878 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:24.879 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.890 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317024824&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.890 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317024824&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.905 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:24.906 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.919 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.929 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317024824&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.930 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:24.935 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
7.846 ±(99.9%) 0.221 ms/op
Iteration   1: 00:30:27.281 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.286 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x6e4c1433, L:/10.1.0.60:46120 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.287 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:46120 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.289 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.289 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.290 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.290 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.290 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:27.291 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.298 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317024824&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.299 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317024824&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.299 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.300 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.300 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.301 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.302 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.302 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.303 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.305 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.305 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.305 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.307 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.307 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:29.309 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3f27ae26, dubbo version: 3.2.7, current host: 10.1.0.60
3.333 ±(99.9%) 0.140 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   5.851 ms/op
                 createUser·p0.99:   11.190 ms/op
                 createUser·p0.999:  71.434 ms/op
                 createUser·p0.9999: 71.434 ms/op
                 createUser·p1.00:   71.434 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9714
  mean =      3.333 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8970 
    [ 5.000, 10.000) = 552 
    [10.000, 15.000) = 127 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.851 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     71.434 ms/op
     p(99.9900) =     71.434 ms/op
     p(99.9990) =     71.434 ms/op
     p(99.9999) =     71.434 ms/op
    p(100.0000) =     71.434 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:31.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.310 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.369 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.371 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.391 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.392 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.409 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.410 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.458 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.624 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.624 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.632 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.633 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.639 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.641 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.653 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.654 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.658 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.659 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.660 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.661 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.661 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@34a1c988, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.833 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.866 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.905 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.964 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.966 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.966 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.966 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:31.993 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.003 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.013 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.067 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.230 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.231 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.231 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.232 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.424 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.refer(QosProtocolWrapper.java:84)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.refer(ProtocolSecurityWrapper.java:110)
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
00:30:32.425 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.559 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xb879df9a, L:/10.1.0.60:44136 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.560 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.564 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:44136 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.595 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.597 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:32.611 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.612 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.619 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.625 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.693 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:32.749 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
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
00:30:32.750 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.752 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3251&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317032688&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.753 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3251&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317032688&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.769 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
org.apache.dubbo.qos.server.QosBindException: qos-server can not bind localhost:22222
	at org.apache.dubbo.qos.server.Server.start(Server.java:125)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.startQosServer(QosProtocolWrapper.java:133)
	at org.apache.dubbo.qos.protocol.QosProtocolWrapper.export(QosProtocolWrapper.java:78)
	at org.apache.dubbo.rpc.protocol.ProtocolSecurityWrapper.export(ProtocolSecurityWrapper.java:83)
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
00:30:32.770 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.781 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.789 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3251&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317032688&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.790 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:32.794 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
4.622 ±(99.9%) 0.146 ms/op
Iteration   1: 00:30:35.043 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.045 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xb879df9a, L:/10.1.0.60:44136 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.047 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.048 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.048 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.048 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:44136 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.048 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.052 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:35.053 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3251&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317032688&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3251&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317032688&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.063 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.063 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.064 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.067 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.067 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.068 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.068 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.068 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.068 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.068 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.070 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.070 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.070 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.071 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.071 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.073 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.073 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:37.077 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@34a1c988, dubbo version: 3.2.7, current host: 10.1.0.60
2.054 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.839 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  22.053 ms/op
                 existUser·p0.9999: 23.065 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15567
  mean =      2.054 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14423 
    [ 2.500,  5.000) = 941 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     23.065 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 00:30:39.098 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.119 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.204 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.206 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.219 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.220 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.261 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.414 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.414 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.421 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.422 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.426 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.427 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.434 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.435 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.437 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.438 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.438 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.639 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.674 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.711 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.769 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.793 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.805 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.816 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:39.865 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.022 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.023 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.023 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.024 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.155 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:40.156 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.295 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x61509fde, L:/10.1.0.60:34492 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.295 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.299 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:34492 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.322 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.323 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:40.340 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.341 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.346 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.348 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.418 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:40.468 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:40.469 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.482 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3346&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317040409&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.482 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3346&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317040409&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.497 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:40.498 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.507 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.518 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3346&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317040409&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.519 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:40.525 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
7.951 ±(99.9%) 0.247 ms/op
Iteration   1: 00:30:42.784 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.786 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x61509fde, L:/10.1.0.60:34492 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.791 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.793 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.793 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.794 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.794 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.795 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:42.795 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:34492 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.806 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3346&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317040409&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.806 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3346&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317040409&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.807 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.807 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.808 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.809 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.809 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.811 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.812 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.812 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.812 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.815 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.815 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:44.816 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.60
3.445 ±(99.9%) 0.083 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   14.934 ms/op
                 getUser·p0.999:  33.852 ms/op
                 getUser·p0.9999: 38.863 ms/op
                 getUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9222
  mean =      3.445 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1369 
    [ 2.500,  5.000) = 7159 
    [ 5.000,  7.500) = 357 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      6.193 ms/op
     p(99.0000) =     14.934 ms/op
     p(99.9000) =     33.852 ms/op
     p(99.9900) =     38.863 ms/op
     p(99.9990) =     38.863 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 00:30:46.867 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:46.900 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:46.965 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:46.966 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:46.983 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:46.984 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:46.999 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.000 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.044 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.199 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.199 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.203 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.203 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.206 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.206 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.228 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.229 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.232 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.237 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.238 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.240 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.242 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7977fecf, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.401 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.425 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.473 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.536 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.539 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.540 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.540 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.575 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.589 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.595 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.639 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.797 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.798 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.798 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.799 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:47.957 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:47.958 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.118 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.60:8080 from NettyClient 10.1.0.60 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xcd7e69dc, L:/10.1.0.60:34508 - R:/10.1.0.60:8080]], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.118 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.60 connect to the server /10.1.0.60:8080, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.123 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:34508 -> /10.1.0.60:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.156 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.158 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
00:30:48.172 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.173 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.179 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.185 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.232 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.60, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
00:30:48.291 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:48.292 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.295 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317048229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.295 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317048229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.313 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.60, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
00:30:48.314 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.321 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.331 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317048229&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.331 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:48.337 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.60
21.101 ±(99.9%) 0.695 ms/op
Iteration   1: 00:30:50.654 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.656 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xcd7e69dc, L:/10.1.0.60:34508 - R:/10.1.0.60:8080], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.658 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.60:34508 -> /10.1.0.60:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.660 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.660 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.660 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.683 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.684 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:50.684 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.60:20880, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.691 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.60:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317048229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.692 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.60&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699317048229&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.692 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.692 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.693 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.694 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.694 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.696 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.696 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.696 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.60
00:30:52.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-11] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7977fecf, dubbo version: 3.2.7, current host: 10.1.0.60
15.169 ±(99.9%) 0.396 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   14.352 ms/op
                 listUser·p0.90:   20.641 ms/op
                 listUser·p0.95:   23.298 ms/op
                 listUser·p0.99:   44.131 ms/op
                 listUser·p0.999:  55.207 ms/op
                 listUser·p0.9999: 59.965 ms/op
                 listUser·p1.00:   59.965 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2160
  mean =     15.169 ±(99.9%) 0.396 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15 
    [ 5.000, 10.000) = 221 
    [10.000, 15.000) = 1026 
    [15.000, 20.000) = 644 
    [20.000, 25.000) = 171 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 10 
    [45.000, 50.000) = 17 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =     14.352 ms/op
     p(90.0000) =     20.641 ms/op
     p(95.0000) =     23.298 ms/op
     p(99.0000) =     44.131 ms/op
     p(99.9000) =     55.207 ms/op
     p(99.9900) =     59.965 ms/op
     p(99.9990) =     59.965 ms/op
     p(99.9999) =     59.965 ms/op
    p(100.0000) =     59.965 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.024          ops/ms
Client.existUser                       thrpt         12.549          ops/ms
Client.getUser                         thrpt          5.978          ops/ms
Client.listUser                        thrpt          1.961          ops/ms
Client.createUser                       avgt          4.646           ms/op
Client.existUser                        avgt          2.257           ms/op
Client.getUser                          avgt          3.274           ms/op
Client.listUser                         avgt         17.155           ms/op
Client.createUser                     sample   9714   3.333 ± 0.140   ms/op
Client.createUser:createUser·p0.00    sample          1.026           ms/op
Client.createUser:createUser·p0.50    sample          2.642           ms/op
Client.createUser:createUser·p0.90    sample          4.293           ms/op
Client.createUser:createUser·p0.95    sample          5.851           ms/op
Client.createUser:createUser·p0.99    sample         11.190           ms/op
Client.createUser:createUser·p0.999   sample         71.434           ms/op
Client.createUser:createUser·p0.9999  sample         71.434           ms/op
Client.createUser:createUser·p1.00    sample         71.434           ms/op
Client.existUser                      sample  15567   2.054 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.799           ms/op
Client.existUser:existUser·p0.50      sample          1.870           ms/op
Client.existUser:existUser·p0.90      sample          2.335           ms/op
Client.existUser:existUser·p0.95      sample          2.839           ms/op
Client.existUser:existUser·p0.99      sample          5.415           ms/op
Client.existUser:existUser·p0.999     sample         22.053           ms/op
Client.existUser:existUser·p0.9999    sample         23.065           ms/op
Client.existUser:existUser·p1.00      sample         23.101           ms/op
Client.getUser                        sample   9222   3.445 ± 0.083   ms/op
Client.getUser:getUser·p0.00          sample          0.495           ms/op
Client.getUser:getUser·p0.50          sample          2.961           ms/op
Client.getUser:getUser·p0.90          sample          4.358           ms/op
Client.getUser:getUser·p0.95          sample          6.193           ms/op
Client.getUser:getUser·p0.99          sample         14.934           ms/op
Client.getUser:getUser·p0.999         sample         33.852           ms/op
Client.getUser:getUser·p0.9999        sample         38.863           ms/op
Client.getUser:getUser·p1.00          sample         38.863           ms/op
Client.listUser                       sample   2160  15.169 ± 0.396   ms/op
Client.listUser:listUser·p0.00        sample          1.163           ms/op
Client.listUser:listUser·p0.50        sample         14.352           ms/op
Client.listUser:listUser·p0.90        sample         20.641           ms/op
Client.listUser:listUser·p0.95        sample         23.298           ms/op
Client.listUser:listUser·p0.99        sample         44.131           ms/op
Client.listUser:listUser·p0.999       sample         55.207           ms/op
Client.listUser:listUser·p0.9999      sample         59.965           ms/op
Client.listUser:listUser·p1.00        sample         59.965           ms/op
```
