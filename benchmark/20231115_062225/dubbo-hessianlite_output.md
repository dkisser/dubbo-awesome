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
[INFO] benchmark-base ..................................... SUCCESS [  4.594 s]
[INFO] server-base ........................................ SUCCESS [  0.572 s]
[INFO] client-base ........................................ SUCCESS [  0.935 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  0.518 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  7.112 s
[INFO] Finished at: 2023-11-15T06:09:15Z
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
# Warmup Iteration   1: 06:09:17.414 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.443 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.525 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.527 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.547 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.548 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.563 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.564 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.605 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.802 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.802 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.811 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.812 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.820 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.821 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.844 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.845 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.849 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.852 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.853 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.855 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:17.855 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.095 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.145 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.182 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.270 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.277 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.280 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.281 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.327 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.342 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.351 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.424 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.621 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.621 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.622 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.622 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.834 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:18.837 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.977 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x801974f6, L:/10.1.0.59:40264 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.977 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:18.982 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:40264 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.040 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.042 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:09:19.062 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.063 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.070 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.076 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.156 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:09:19.230 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:19.230 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.238 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2200&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028559150&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.239 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2200&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028559150&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.258 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:19.258 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.266 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.277 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2200&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028559150&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.278 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:19.283 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
0.886 ops/ms
Iteration   1: 06:09:21.362 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.364 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x801974f6, L:/10.1.0.59:40264 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.370 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:40264 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.377 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.377 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.378 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.378 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.379 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:21.379 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.389 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2200&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028559150&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.389 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2200&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028559150&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.389 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.390 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.391 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.392 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.393 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.395 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.397 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.397 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.397 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.398 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:23.402 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.59
2.290 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.290 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:29
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:25.497 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.525 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.601 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.603 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.625 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.625 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.641 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.642 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.687 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.895 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.896 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.902 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.902 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.905 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.906 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.918 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.918 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.922 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.924 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.926 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:25.927 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@49cbb02c, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.158 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.187 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.240 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.325 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.327 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.327 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.328 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.362 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.372 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.381 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.635 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.636 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.636 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.637 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:26.816 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:26.817 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.010 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:50452 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.023 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x1a267162, L:/10.1.0.59:50452 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.023 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.077 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.080 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:09:27.105 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.106 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.113 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.115 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.174 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:09:27.249 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:27.250 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.269 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2498&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028567170&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.269 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2498&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028567170&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.286 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:27.286 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.303 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.313 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2498&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028567170&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.314 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:27.319 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
2.467 ops/ms
Iteration   1: 06:09:29.371 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.376 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1a267162, L:/10.1.0.59:50452 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.378 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:50452 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.387 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.387 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.388 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.388 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.388 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:29.389 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.417 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2498&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028567170&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.417 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2498&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028567170&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.418 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.418 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.419 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.420 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.421 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.424 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.424 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.425 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.426 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:31.429 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-19] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@49cbb02c, dubbo version: 3.2.7, current host: 10.1.0.59
6.203 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.203 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:33.477 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.518 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.591 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.593 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.617 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.618 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.631 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.632 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.687 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.860 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.862 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.870 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.871 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.874 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.874 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.884 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.884 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.887 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.889 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.890 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.903 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:33.903 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.092 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.147 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.206 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.284 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.289 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.289 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.289 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.322 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.338 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.341 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.388 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.547 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.548 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.548 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.548 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.705 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:34.706 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.868 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:55646 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.870 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x1c0778de, L:/10.1.0.59:55646 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.871 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.916 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.918 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:09:34.935 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.936 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.942 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:34.945 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.025 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:09:35.086 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:35.086 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.107 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2593&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028575017&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.107 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2593&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028575017&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.126 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:35.127 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.136 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.143 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2593&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028575017&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.144 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:35.150 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
2.063 ops/ms
Iteration   1: 06:09:37.241 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.244 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1c0778de, L:/10.1.0.59:55646 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.246 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:55646 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.261 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.262 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.262 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.262 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.263 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:37.263 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.297 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2593&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028575017&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.298 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2593&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028575017&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.298 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.299 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.299 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.301 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.301 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.302 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.302 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.302 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.302 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.302 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.303 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.303 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.303 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.303 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.304 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.304 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.308 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.308 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:39.310 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-16] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.59
3.171 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.171 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:41.254 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.354 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.355 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.377 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.378 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.393 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.394 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.433 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.614 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.615 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.620 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.620 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.623 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.624 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.634 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.634 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.636 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.639 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.639 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.641 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.641 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.851 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.888 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:41.948 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.028 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.034 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.037 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.083 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.095 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.100 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.147 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.351 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.354 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.355 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.356 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.556 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:42.558 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.726 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x4befe90a, L:/10.1.0.59:55648 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.726 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.728 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:55648 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.772 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.774 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:09:42.792 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.792 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.797 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.799 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.843 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:09:42.878 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:42.879 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.898 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028582840&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.898 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028582840&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.914 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:42.914 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.928 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.940 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028582840&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.941 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:42.946 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
0.837 ops/ms
Iteration   1: 06:09:45.098 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.101 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x4befe90a, L:/10.1.0.59:55648 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.102 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:55648 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.108 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.108 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.111 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.112 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.112 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:45.113 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.133 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028582840&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.134 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028582840&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.134 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.135 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.135 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.136 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.139 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.140 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.140 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.140 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.140 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.140 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.140 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.141 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.141 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.141 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.141 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.142 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.146 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.146 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:47.148 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.59
1.360 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.360 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:49.117 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.141 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.207 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.208 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.227 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.228 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.241 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.242 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.278 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.498 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.498 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.505 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.506 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.513 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.513 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.523 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.523 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.526 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.528 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.528 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.530 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.530 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.732 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.772 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.836 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.902 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.903 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.904 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.911 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.937 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.950 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:49.955 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.008 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.165 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.168 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.168 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.169 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.340 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:50.341 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.471 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x51a87d83, L:/10.1.0.59:36268 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.471 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.473 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:36268 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.502 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.504 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:09:50.514 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.515 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.520 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.521 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.561 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:09:50.606 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:50.607 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.614 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2786&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028590557&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.614 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2786&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028590557&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.637 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:50.638 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.645 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.653 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2786&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028590557&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.654 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:50.659 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
12.765 ±(99.9%) 0.305 ms/op
Iteration   1: 06:09:52.724 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.730 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x51a87d83, L:/10.1.0.59:36268 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.731 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:36268 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.739 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.739 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.739 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.740 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.740 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:52.741 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.765 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2786&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028590557&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.766 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2786&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028590557&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.766 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.766 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.767 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.768 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.769 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.771 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.771 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.772 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.772 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.772 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.772 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.772 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.773 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.773 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.773 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.774 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.775 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.776 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:54.777 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-32] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.59
6.330 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.330 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 06:09:56.735 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.777 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.855 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.857 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.879 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.880 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.894 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.894 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:56.936 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.095 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.096 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.102 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.103 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.106 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.106 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.118 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.118 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.121 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.123 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.123 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.125 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.125 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@14a3d717, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.351 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.385 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.420 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.517 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.520 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.522 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.524 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.553 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.565 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.568 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.614 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.799 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.800 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.801 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.802 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:57.980 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:57.981 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.148 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:35996 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.149 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xd4ae8379, L:/10.1.0.59:35996 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.153 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.192 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.194 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:09:58.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.223 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.226 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:09:58.311 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:58.312 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.323 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2881&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028598263&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.324 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2881&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028598263&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.345 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:09:58.346 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.354 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.366 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2881&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028598263&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.367 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:09:58.372 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
10.916 ±(99.9%) 0.206 ms/op
Iteration   1: 06:10:00.419 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.421 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xd4ae8379, L:/10.1.0.59:35996 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.432 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.432 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.433 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.434 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.434 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:00.444 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:35996 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.454 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2881&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028598263&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.455 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2881&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028598263&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.455 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.456 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.457 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.458 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.460 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.461 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.461 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.461 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.462 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.462 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.462 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.465 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.465 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:02.466 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@14a3d717, dubbo version: 3.2.7, current host: 10.1.0.59
4.935 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.935 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 06:10:04.496 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.525 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.602 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.604 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.627 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.629 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.646 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.647 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.695 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.914 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.914 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.923 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.924 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.929 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.930 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.940 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.940 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.943 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.945 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.945 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.947 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:04.947 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.129 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.157 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.212 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.290 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.291 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.292 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.292 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.328 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.336 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.401 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.591 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.592 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.594 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.595 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.792 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:05.793 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.977 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xe5db54c6, L:/10.1.0.59:33580 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.977 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:05.981 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:33580 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.017 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.019 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:10:06.035 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.036 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.122 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:10:06.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:06.187 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.201 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2974&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028606118&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.201 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2974&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028606118&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.217 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:06.218 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.227 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.234 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2974&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028606118&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.235 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:06.240 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
11.366 ±(99.9%) 0.256 ms/op
Iteration   1: 06:10:08.291 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.296 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xe5db54c6, L:/10.1.0.59:33580 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.299 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.300 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.300 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.300 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:33580 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.301 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.301 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:08.302 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.310 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2974&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028606118&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.311 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2974&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028606118&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.311 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.311 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.312 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.313 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.314 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.315 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.316 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.316 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.317 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.317 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.317 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.319 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.319 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:10.326 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.59
7.080 ±(99.9%) 0.147 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.080 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 06:10:12.251 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.275 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.345 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.347 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.367 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.367 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.381 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.426 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.636 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.637 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.645 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.646 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.652 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.653 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.678 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.681 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.682 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.685 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.687 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.908 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:12.949 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.029 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.095 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.097 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.097 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.098 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.122 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.130 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.137 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.185 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.354 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.355 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.355 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.355 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.553 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:13.554 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.691 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xe74de61c, L:/10.1.0.59:49840 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.692 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.696 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:49840 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.730 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.732 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:10:13.750 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.750 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.756 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.757 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.840 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:10:13.901 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:13.903 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.920 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3070&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028613833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.920 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3070&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028613833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.941 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:13.942 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.950 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.958 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3070&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028613833&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.958 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:13.963 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
32.710 ±(99.9%) 1.128 ms/op
Iteration   1: 06:10:16.065 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.067 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xe74de61c, L:/10.1.0.59:49840 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.071 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:49840 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.076 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.076 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.077 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.077 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.078 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:16.078 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.098 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3070&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028613833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.099 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3070&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028613833&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.099 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.100 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.101 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.102 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.103 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.105 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.105 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.105 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.105 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.105 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.106 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.106 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.106 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.107 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.107 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.107 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.110 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.110 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:18.112 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.59
21.037 ±(99.9%) 0.271 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.037 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 06:10:20.108 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.136 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.217 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.219 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.240 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.241 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.255 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.257 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.306 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.486 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.486 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.492 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.492 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.495 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.496 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.506 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.507 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.509 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.512 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.517 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.518 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.519 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.722 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.751 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.801 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.863 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.867 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.868 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.868 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.907 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.923 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.927 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:20.976 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.177 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.178 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.179 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.181 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.335 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:21.336 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.462 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xc276277c, L:/10.1.0.59:49848 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.462 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.466 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:49848 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.501 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.502 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:10:21.522 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.522 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.529 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.532 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.572 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:10:21.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:21.614 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.634 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3165&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028621569&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.634 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3165&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028621569&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.653 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:21.654 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.664 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.672 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3165&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028621569&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.673 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:21.679 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
12.535 ±(99.9%) 0.395 ms/op
Iteration   1: 06:10:23.952 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.955 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xc276277c, L:/10.1.0.59:49848 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.956 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:49848 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.961 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.962 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.962 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.962 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.963 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:23.963 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.969 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3165&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028621569&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.969 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3165&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028621569&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.969 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.970 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.971 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.972 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.973 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.973 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.973 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.973 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.975 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.975 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.976 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.977 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.977 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:25.979 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@56f113e9, dubbo version: 3.2.7, current host: 10.1.0.59
6.596 ±(99.9%) 0.231 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   12.943 ms/op
                 createUser·p0.95:   15.394 ms/op
                 createUser·p0.99:   31.442 ms/op
                 createUser·p0.999:  39.790 ms/op
                 createUser·p0.9999: 40.436 ms/op
                 createUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4848
  mean =      6.596 ±(99.9%) 0.231 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2738 
    [ 5.000, 10.000) = 1314 
    [10.000, 15.000) = 526 
    [15.000, 20.000) = 154 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.722 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =     12.943 ms/op
     p(95.0000) =     15.394 ms/op
     p(99.0000) =     31.442 ms/op
     p(99.9000) =     39.790 ms/op
     p(99.9900) =     40.436 ms/op
     p(99.9990) =     40.436 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 06:10:28.060 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.102 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.174 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.176 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.205 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.206 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.229 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.234 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.290 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.491 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.491 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.500 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.500 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.507 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.508 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.528 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.529 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.532 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.537 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.539 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.541 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.542 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.769 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.795 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.832 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.895 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.897 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.897 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.898 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.939 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.947 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:28.958 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.006 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.213 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.214 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.391 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:29.392 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.536 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xb1b224b9, L:/10.1.0.59:50136 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.536 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:50136 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.536 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.582 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.584 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:10:29.602 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.604 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.614 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.615 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.705 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:10:29.792 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:29.793 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.797 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3261&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028629690&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.797 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3261&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028629690&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:29.818 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.825 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.834 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3261&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028629690&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.835 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:29.841 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
7.541 ±(99.9%) 0.233 ms/op
Iteration   1: 06:10:32.045 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.047 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xb1b224b9, L:/10.1.0.59:50136 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.055 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:50136 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.055 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.056 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.056 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:32.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.085 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3261&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028629690&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.085 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3261&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028629690&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.086 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.086 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.087 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.088 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.089 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.090 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.090 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.090 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.090 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.091 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.091 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.091 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.091 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.092 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.092 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.092 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.094 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.094 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:34.096 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.59
3.205 ±(99.9%) 0.066 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.728 ms/op
                 existUser·p0.90:   5.144 ms/op
                 existUser·p0.95:   7.619 ms/op
                 existUser·p0.99:   11.272 ms/op
                 existUser·p0.999:  19.096 ms/op
                 existUser·p0.9999: 20.938 ms/op
                 existUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10030
  mean =      3.205 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3799 
    [ 2.500,  5.000) = 5196 
    [ 5.000,  7.500) = 496 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      5.144 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     19.096 ms/op
     p(99.9900) =     20.938 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 06:10:36.096 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.123 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.190 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.191 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.212 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.213 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.227 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.228 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.276 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.440 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.441 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.449 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.450 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.459 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.459 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.462 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.464 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.465 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.468 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.469 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3f27ae26, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.707 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.742 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.791 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.875 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.876 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.880 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.887 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.916 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.934 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.938 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:36.994 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.192 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.193 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.193 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.193 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.365 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:37.375 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.564 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xcea49349, L:/10.1.0.59:53718 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.565 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:53718 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.565 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.613 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.615 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:10:37.631 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.632 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.638 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.639 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.729 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:10:37.776 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:37.776 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.789 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3355&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028637717&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.790 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3355&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028637717&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.809 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:37.810 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.818 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.826 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3355&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028637717&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.826 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:37.832 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
10.531 ±(99.9%) 0.313 ms/op
Iteration   1: 06:10:40.018 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.024 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xcea49349, L:/10.1.0.59:53718 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.029 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.029 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.029 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:40.031 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:53718 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.038 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3355&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028637717&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.039 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3355&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028637717&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.039 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.039 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.040 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.042 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.047 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.047 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:42.048 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@3f27ae26, dubbo version: 3.2.7, current host: 10.1.0.59
4.978 ±(99.9%) 0.096 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   8.279 ms/op
                 getUser·p0.99:   15.804 ms/op
                 getUser·p0.999:  27.589 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6527
  mean =      4.978 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 4777 
    [ 5.000,  7.500) = 1337 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      8.279 ms/op
     p(99.0000) =     15.804 ms/op
     p(99.9000) =     27.589 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 06:10:44.179 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.217 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.285 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.287 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.306 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.307 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.325 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.326 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.371 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.547 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.547 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.552 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.552 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.555 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.556 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.565 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.566 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.568 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.570 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.571 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.572 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.857 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.898 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:44.951 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.041 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.041 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.042 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.074 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.085 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.088 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.143 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.342 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.343 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.343 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.344 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.550 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:45.551 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.678 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.59:8080 from NettyClient 10.1.0.59 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xdc745cef, L:/10.1.0.59:37102 - R:/10.1.0.59:8080]], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.680 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.59 connect to the server /10.1.0.59:8080, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.685 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:37102 -> /10.1.0.59:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.718 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
06:10:45.740 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.740 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.746 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.748 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.820 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.59, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
06:10:45.866 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:45.866 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.875 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3453&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028645816&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.875 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3453&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028645816&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.894 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.59, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
06:10:45.894 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.902 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.912 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3453&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028645816&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.913 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:45.918 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.59
26.287 ±(99.9%) 1.177 ms/op
Iteration   1: 06:10:48.152 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.158 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xdc745cef, L:/10.1.0.59:37102 - R:/10.1.0.59:8080], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.159 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.59:37102 -> /10.1.0.59:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.165 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.166 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.166 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.166 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.167 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:48.167 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.59:20880, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.59:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3453&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028645816&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.59&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3453&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1700028645816&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.184 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.185 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.188 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.189 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.189 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.189 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.189 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.189 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.189 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.190 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.190 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.191 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.191 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.192 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.192 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.59
06:10:50.195 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-31] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.59
17.125 ±(99.9%) 0.404 ms/op
                 listUser·p0.00:   6.636 ms/op
                 listUser·p0.50:   15.671 ms/op
                 listUser·p0.90:   24.900 ms/op
                 listUser·p0.95:   27.689 ms/op
                 listUser·p0.99:   33.790 ms/op
                 listUser·p0.999:  48.208 ms/op
                 listUser·p0.9999: 49.873 ms/op
                 listUser·p1.00:   49.873 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1940
  mean =     17.125 ±(99.9%) 0.404 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 40 
    [10.000, 15.000) = 830 
    [15.000, 20.000) = 621 
    [20.000, 25.000) = 256 
    [25.000, 30.000) = 126 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      6.636 ms/op
     p(50.0000) =     15.671 ms/op
     p(90.0000) =     24.900 ms/op
     p(95.0000) =     27.689 ms/op
     p(99.0000) =     33.790 ms/op
     p(99.9000) =     48.208 ms/op
     p(99.9900) =     49.873 ms/op
     p(99.9990) =     49.873 ms/op
     p(99.9999) =     49.873 ms/op
    p(100.0000) =     49.873 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.290          ops/ms
Client.existUser                       thrpt          6.203          ops/ms
Client.getUser                         thrpt          3.171          ops/ms
Client.listUser                        thrpt          1.360          ops/ms
Client.createUser                       avgt          6.330           ms/op
Client.existUser                        avgt          4.935           ms/op
Client.getUser                          avgt          7.080           ms/op
Client.listUser                         avgt         21.037           ms/op
Client.createUser                     sample   4848   6.596 ± 0.231   ms/op
Client.createUser:createUser·p0.00    sample          1.722           ms/op
Client.createUser:createUser·p0.50    sample          4.678           ms/op
Client.createUser:createUser·p0.90    sample         12.943           ms/op
Client.createUser:createUser·p0.95    sample         15.394           ms/op
Client.createUser:createUser·p0.99    sample         31.442           ms/op
Client.createUser:createUser·p0.999   sample         39.790           ms/op
Client.createUser:createUser·p0.9999  sample         40.436           ms/op
Client.createUser:createUser·p1.00    sample         40.436           ms/op
Client.existUser                      sample  10030   3.205 ± 0.066   ms/op
Client.existUser:existUser·p0.00      sample          0.861           ms/op
Client.existUser:existUser·p0.50      sample          2.728           ms/op
Client.existUser:existUser·p0.90      sample          5.144           ms/op
Client.existUser:existUser·p0.95      sample          7.619           ms/op
Client.existUser:existUser·p0.99      sample         11.272           ms/op
Client.existUser:existUser·p0.999     sample         19.096           ms/op
Client.existUser:existUser·p0.9999    sample         20.938           ms/op
Client.existUser:existUser·p1.00      sample         20.939           ms/op
Client.getUser                        sample   6527   4.978 ± 0.096   ms/op
Client.getUser:getUser·p0.00          sample          1.268           ms/op
Client.getUser:getUser·p0.50          sample          4.473           ms/op
Client.getUser:getUser·p0.90          sample          6.177           ms/op
Client.getUser:getUser·p0.95          sample          8.279           ms/op
Client.getUser:getUser·p0.99          sample         15.804           ms/op
Client.getUser:getUser·p0.999         sample         27.589           ms/op
Client.getUser:getUser·p0.9999        sample         28.115           ms/op
Client.getUser:getUser·p1.00          sample         28.115           ms/op
Client.listUser                       sample   1940  17.125 ± 0.404   ms/op
Client.listUser:listUser·p0.00        sample          6.636           ms/op
Client.listUser:listUser·p0.50        sample         15.671           ms/op
Client.listUser:listUser·p0.90        sample         24.900           ms/op
Client.listUser:listUser·p0.95        sample         27.689           ms/op
Client.listUser:listUser·p0.99        sample         33.790           ms/op
Client.listUser:listUser·p0.999       sample         48.208           ms/op
Client.listUser:listUser·p0.9999      sample         49.873           ms/op
Client.listUser:listUser·p1.00        sample         49.873           ms/op
```
