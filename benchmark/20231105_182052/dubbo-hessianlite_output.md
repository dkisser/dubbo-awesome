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
[INFO] benchmark-base ..................................... SUCCESS [  3.764 s]
[INFO] server-base ........................................ SUCCESS [  0.481 s]
[INFO] client-base ........................................ SUCCESS [  0.713 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  0.418 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.791 s
[INFO] Finished at: 2023-11-05T18:07:16Z
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
# Warmup Iteration   1: 18:07:17.203 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.240 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.305 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.306 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.323 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.324 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.342 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.343 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.388 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.570 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.570 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.574 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.574 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.577 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.577 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.589 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.592 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.595 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.600 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.600 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.603 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.603 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6d992f23, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.805 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.837 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.894 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.970 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.972 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:17.974 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.019 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.027 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.034 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.081 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.251 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.251 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.252 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.254 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.418 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:18.418 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.579 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xa3619b8d, L:/10.1.0.45:45602 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.580 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.590 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:45602 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.634 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.636 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:07:18.650 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.651 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.656 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.658 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.723 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:07:18.786 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:18.786 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.800 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2167&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207638713&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.800 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2167&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207638713&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.815 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:18.815 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.826 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.837 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2167&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207638713&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.838 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:18.843 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
1.403 ops/ms
Iteration   1: 18:07:20.944 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.946 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xa3619b8d, L:/10.1.0.45:45602 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.947 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:45602 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.955 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.956 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.956 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.956 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:20.957 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.978 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2167&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207638713&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.978 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2167&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207638713&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.978 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.979 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.980 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.981 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.981 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.983 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.983 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.983 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.983 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.983 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.984 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.985 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.988 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.991 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.991 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:22.993 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6d992f23, dubbo version: 3.2.7, current host: 10.1.0.45
4.223 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.223 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 18:07:24.849 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.872 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.934 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.936 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.959 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.960 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.977 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:24.978 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.027 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.212 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.212 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.219 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.219 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.222 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.222 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.230 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.231 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.233 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.235 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.235 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.240 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.240 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.439 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.469 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.506 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.556 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.558 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.558 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.559 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.582 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.590 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.597 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.659 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.842 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.843 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.843 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:25.844 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.021 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:26.022 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.161 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:45616 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.161 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x31fad538, L:/10.1.0.45:45616 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.163 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.194 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.196 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:07:26.205 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.206 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.210 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.211 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.247 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:07:26.311 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:26.311 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.319 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2467&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207646244&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.319 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2467&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207646244&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.339 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:26.339 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.347 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.355 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2467&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207646244&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.355 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:26.361 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
3.614 ops/ms
Iteration   1: 18:07:28.413 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.418 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x31fad538, L:/10.1.0.45:45616 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.419 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:45616 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.422 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.423 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:28.424 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.431 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2467&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207646244&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.432 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2467&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207646244&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.432 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.432 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.433 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.434 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.437 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.437 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.443 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.444 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:30.446 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-11] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.45
8.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.379 ops/ms


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
# Warmup Iteration   1: 18:07:32.291 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.322 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.383 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.385 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.402 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.403 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.417 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.418 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.465 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.646 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.647 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.654 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.654 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.657 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.657 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.674 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.675 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.678 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.684 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.684 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.698 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.699 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@525ea615, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.892 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.922 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:32.978 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.047 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.047 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.072 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.085 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.092 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.137 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.310 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.311 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.313 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.313 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.487 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:33.489 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.631 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x1836374d, L:/10.1.0.45:46476 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.631 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.636 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:46476 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.669 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.671 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:07:33.685 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.687 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.694 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.695 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.761 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:07:33.817 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:33.817 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.820 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2563&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207653750&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.820 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2563&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207653750&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.843 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:33.843 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.851 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.860 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2563&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207653750&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.860 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:33.866 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
2.870 ops/ms
Iteration   1: 18:07:35.915 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.917 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1836374d, L:/10.1.0.45:46476 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.922 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:46476 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.929 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.929 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.929 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.930 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.930 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:35.930 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.938 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2563&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207653750&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.944 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2563&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207653750&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.944 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.945 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.946 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.949 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.950 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.952 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.953 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.953 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.953 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.954 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.955 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:37.957 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@525ea615, dubbo version: 3.2.7, current host: 10.1.0.45
5.138 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.138 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 18:07:39.835 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.872 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.932 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.934 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.956 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.957 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.969 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:39.970 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.013 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.162 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.162 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.166 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.167 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.169 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.170 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.191 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.191 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.193 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.195 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.195 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.197 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.197 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4a72098a, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.374 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.418 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.465 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.527 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.529 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.529 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.529 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.563 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.574 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.579 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.629 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.789 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.791 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.791 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.792 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:40.953 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:40.953 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.086 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x26b8eb4d, L:/10.1.0.45:48880 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.087 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.088 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:48880 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.134 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.136 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:07:41.147 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.148 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.156 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.157 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.194 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:07:41.248 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:41.249 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.255 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2662&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207661191&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.256 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2662&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207661191&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.275 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:41.275 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.283 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.296 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2662&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207661191&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.297 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:41.302 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
1.005 ops/ms
Iteration   1: 18:07:43.440 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.443 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x26b8eb4d, L:/10.1.0.45:48880 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.445 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:48880 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.452 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.452 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.452 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.453 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.453 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:43.453 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.465 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2662&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207661191&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.466 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2662&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207661191&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.466 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.466 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.467 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.468 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.470 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.471 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.472 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.473 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.473 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.473 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.474 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.475 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.475 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.476 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.476 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.476 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.479 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.479 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:45.484 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4a72098a, dubbo version: 3.2.7, current host: 10.1.0.45
1.308 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.308 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 18:07:47.309 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.340 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.408 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.409 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.431 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.432 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.452 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.453 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.489 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.652 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.653 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.656 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.657 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.659 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.660 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.678 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.678 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.680 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.683 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.684 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.685 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.685 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.877 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.906 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:47.941 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.010 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.011 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.012 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.019 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.057 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.068 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.078 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.118 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.288 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.293 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.295 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.295 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.458 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:48.460 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.604 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x76d06095, L:/10.1.0.45:54026 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.605 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.610 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:54026 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.643 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.644 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:07:48.660 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.665 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.670 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.672 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.741 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:07:48.821 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:48.821 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.840 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207668729&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.840 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207668729&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:48.865 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.897 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.904 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207668729&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.905 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:48.910 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
10.438 ±(99.9%) 0.221 ms/op
Iteration   1: 18:07:50.966 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.968 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x76d06095, L:/10.1.0.45:54026 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.971 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:54026 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.986 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.986 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:50.988 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.010 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207668729&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.010 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2868&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207668729&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.010 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.011 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.012 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.013 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.015 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.016 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.017 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.017 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.017 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.018 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.018 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.019 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.020 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:53.022 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.45
5.256 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.256 ms/op


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
# Warmup Iteration   1: 18:07:54.859 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:54.896 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:54.958 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:54.960 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:54.976 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:54.977 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:54.999 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.000 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.042 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.228 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.228 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.236 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.237 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.240 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.240 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.248 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.248 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.250 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.252 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.252 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.254 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.254 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.426 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.453 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.570 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.572 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.572 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.573 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.592 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.600 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.607 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.661 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.821 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.822 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.824 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.825 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:55.990 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:55.991 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.143 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x1639dbcb, L:/10.1.0.45:54034 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.144 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.146 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:54034 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.182 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.184 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:07:56.200 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.201 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.208 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.210 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.278 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:07:56.328 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:56.329 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.344 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2964&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207676267&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.344 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2964&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207676267&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.358 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:07:56.359 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.369 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.379 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2964&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207676267&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.379 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:56.385 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
6.685 ±(99.9%) 0.080 ms/op
Iteration   1: 18:07:58.431 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.433 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1639dbcb, L:/10.1.0.45:54034 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.434 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:54034 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.446 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.447 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.447 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:07:58.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.478 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2964&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207676267&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.479 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2964&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207676267&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.479 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.480 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.480 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.482 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.482 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.483 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.484 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.484 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.484 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.486 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.486 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:00.488 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.45
2.396 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.396 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:02.338 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.379 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.444 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.446 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.464 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.465 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.478 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.479 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.519 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.707 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.708 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.712 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.712 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.714 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.715 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.723 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.723 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.725 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.727 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.728 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.729 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.729 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@49cbb02c, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.944 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:02.984 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.036 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.113 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.116 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.117 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.117 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.135 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.146 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.153 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.196 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.361 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.362 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.365 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.531 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:03.532 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.693 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x1a533ea8, L:/10.1.0.45:42020 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.694 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.698 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:42020 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.733 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.735 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:03.750 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.751 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.762 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.764 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.825 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:03.907 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:03.907 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.922 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3057&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207683814&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.922 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3057&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207683814&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.943 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:03.944 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.951 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.958 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3057&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207683814&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.959 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:03.964 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
14.314 ±(99.9%) 0.181 ms/op
Iteration   1: 18:08:06.015 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.017 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x1a533ea8, L:/10.1.0.45:42020 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.020 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:42020 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.024 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.025 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.026 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.029 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.030 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:06.031 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3057&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207683814&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3057&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207683814&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.042 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.045 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.046 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.050 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.053 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:08.055 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@49cbb02c, dubbo version: 3.2.7, current host: 10.1.0.45
5.674 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.674 ms/op


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
# Warmup Iteration   1: 18:08:09.943 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:09.980 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.040 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.041 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.058 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.059 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.084 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.085 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.137 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.324 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.325 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.328 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.329 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.331 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.332 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.340 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.340 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.342 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.344 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.344 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.346 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.346 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.546 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.575 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.625 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.683 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.684 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.685 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.685 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.709 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.724 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.731 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.787 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.951 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.952 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.954 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:10.955 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.119 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:11.120 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.276 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xf173c5bc, L:/10.1.0.45:52014 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.277 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:52014 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.278 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.316 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.317 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:11.333 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.335 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.345 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.346 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.402 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:11.450 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:11.452 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.471 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3151&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207691398&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.471 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3151&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207691398&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.486 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:11.487 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.496 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.506 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3151&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207691398&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.507 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:11.512 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
29.968 ±(99.9%) 1.059 ms/op
Iteration   1: 18:08:13.655 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.657 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xf173c5bc, L:/10.1.0.45:52014 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.660 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:52014 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.670 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.671 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.671 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.671 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.672 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:13.672 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3151&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207691398&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3151&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207691398&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.696 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.696 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.697 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.698 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.701 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.701 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.701 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.703 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.703 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:15.705 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.45
19.383 ±(99.9%) 0.248 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.383 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:17.538 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.571 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.631 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.633 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.653 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.654 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.667 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.668 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.719 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.900 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.901 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.910 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.910 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.917 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.917 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.938 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.938 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.941 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.946 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.948 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.950 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:17.951 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.141 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.166 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.195 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.246 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.287 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.295 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.307 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.361 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.534 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.535 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.537 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.538 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.711 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:18.712 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.844 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x0f6fc86d, L:/10.1.0.45:35590 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.845 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.847 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:35590 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.904 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.907 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:18.920 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.921 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.925 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.926 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:18.980 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:19.037 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:19.038 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.041 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207698973&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.041 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207698973&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.059 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:19.059 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.066 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.073 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207698973&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.074 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:19.078 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
9.920 ±(99.9%) 0.268 ms/op
Iteration   1: 18:08:21.374 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.376 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x0f6fc86d, L:/10.1.0.45:35590 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.377 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:35590 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.382 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.383 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.383 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.383 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.383 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:21.384 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.394 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207698973&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.395 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207698973&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.395 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.395 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.397 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.398 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.402 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.402 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.402 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:23.408 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.45
3.649 ±(99.9%) 0.074 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   4.830 ms/op
                 createUser·p0.95:   6.716 ms/op
                 createUser·p0.99:   11.878 ms/op
                 createUser·p0.999:  23.855 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9003
  mean =      3.649 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 280 
    [ 2.500,  5.000) = 7868 
    [ 5.000,  7.500) = 527 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.830 ms/op
     p(95.0000) =      6.716 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 18:08:25.431 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.466 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.533 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.534 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.552 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.552 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.566 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.567 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.614 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.803 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.804 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.810 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.811 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.816 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.817 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.835 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.835 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.837 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.865 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.866 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.868 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:25.868 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@959f0e0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.078 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.107 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.165 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.233 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.235 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.235 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.235 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.272 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.275 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.335 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.494 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.660 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:26.661 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.794 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x8f198e8b, L:/10.1.0.45:35604 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.794 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.800 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:35604 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.833 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.835 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:26.853 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.854 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.862 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.864 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.928 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:26.975 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:26.976 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.978 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3347&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207706919&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.978 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3347&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207706919&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:26.995 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:26.995 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:27.002 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:27.009 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3347&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207706919&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:27.010 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:27.016 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
5.093 ±(99.9%) 0.172 ms/op
Iteration   1: 18:08:29.325 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.327 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x8f198e8b, L:/10.1.0.45:35604 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.328 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:35604 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.342 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.342 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.343 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.343 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.343 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:29.344 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.359 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3347&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207706919&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.359 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3347&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207706919&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.359 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.360 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.361 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.362 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.364 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.364 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.364 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.364 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.365 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.365 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.365 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.365 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.365 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.366 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.366 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.366 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.367 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.367 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:31.369 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-16] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@959f0e0, dubbo version: 3.2.7, current host: 10.1.0.45
2.499 ±(99.9%) 0.080 ms/op
                 existUser·p0.00:   0.295 ms/op
                 existUser·p0.50:   1.739 ms/op
                 existUser·p0.90:   3.958 ms/op
                 existUser·p0.95:   7.505 ms/op
                 existUser·p0.99:   12.810 ms/op
                 existUser·p0.999:  33.292 ms/op
                 existUser·p0.9999: 33.861 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13156
  mean =      2.499 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11004 
    [ 2.500,  5.000) = 1001 
    [ 5.000,  7.500) = 493 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      3.958 ms/op
     p(95.0000) =      7.505 ms/op
     p(99.0000) =     12.810 ms/op
     p(99.9000) =     33.292 ms/op
     p(99.9900) =     33.861 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 18:08:33.371 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.396 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.468 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.470 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.487 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.488 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.499 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.500 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.541 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.744 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.745 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.751 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.752 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.757 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.758 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.778 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.779 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.782 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.786 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.788 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.806 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:33.806 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@525ea615, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.021 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.050 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.106 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.164 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.169 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.170 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.171 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.196 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.204 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.211 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.263 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.435 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.436 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.438 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.439 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.619 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:34.619 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.779 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x5a744831, L:/10.1.0.45:38906 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.779 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.783 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:38906 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.817 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.819 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:34.837 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.842 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.848 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.850 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.910 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:34.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:34.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.976 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3441&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207714907&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.977 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3441&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207714907&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:34.995 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:34.995 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:35.002 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:35.009 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3441&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207714907&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:35.010 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:35.015 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
8.388 ±(99.9%) 0.218 ms/op
Iteration   1: 18:08:37.339 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.341 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x5a744831, L:/10.1.0.45:38906 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.346 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.347 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.348 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.351 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.352 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.353 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:37.352 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:38906 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.360 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3441&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207714907&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.360 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3441&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207714907&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.360 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.361 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.362 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.362 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.363 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.364 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.365 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.365 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.365 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.367 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.367 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:39.369 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@525ea615, dubbo version: 3.2.7, current host: 10.1.0.45
3.847 ±(99.9%) 0.087 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.832 ms/op
                 getUser·p0.95:   6.667 ms/op
                 getUser·p0.99:   14.849 ms/op
                 getUser·p0.999:  33.280 ms/op
                 getUser·p0.9999: 48.169 ms/op
                 getUser·p1.00:   48.169 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8521
  mean =      3.847 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7755 
    [ 5.000, 10.000) = 610 
    [10.000, 15.000) = 71 
    [15.000, 20.000) = 53 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.832 ms/op
     p(95.0000) =      6.667 ms/op
     p(99.0000) =     14.849 ms/op
     p(99.9000) =     33.280 ms/op
     p(99.9900) =     48.169 ms/op
     p(99.9990) =     48.169 ms/op
     p(99.9999) =     48.169 ms/op
    p(100.0000) =     48.169 ms/op


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
# Warmup Iteration   1: 18:08:41.417 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.447 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.513 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.515 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.536 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.537 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.563 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.565 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.607 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.789 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.789 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.798 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.799 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.801 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.802 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.810 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.810 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.812 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.814 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.814 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.816 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:41.817 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.004 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.027 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.056 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.108 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.109 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.110 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.110 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.144 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.152 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.160 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.211 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.371 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.372 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.372 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.372 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.521 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:42.522 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.677 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.45:8080 from NettyClient 10.1.0.45 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x7495260c, L:/10.1.0.45:41928 - R:/10.1.0.45:8080]], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.678 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.45 connect to the server /10.1.0.45:8080, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.683 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:41928 -> /10.1.0.45:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.719 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:42.735 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.736 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.741 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.743 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.813 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.45, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:42.864 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:42.864 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.881 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3536&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207722804&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.881 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3536&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207722804&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.903 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.45, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:42.904 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.912 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.921 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3536&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207722804&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.921 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:42.927 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.45
22.646 ±(99.9%) 0.843 ms/op
Iteration   1: 18:08:45.163 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.165 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x7495260c, L:/10.1.0.45:41928 - R:/10.1.0.45:8080], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.167 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.45:41928 -> /10.1.0.45:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.170 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.170 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.171 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.172 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.172 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:45.172 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.45:20880, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.178 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.45:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3536&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207722804&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.178 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.45&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3536&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1699207722804&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.178 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.179 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.180 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.181 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.181 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.182 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.183 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.184 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.185 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.45
18:08:47.187 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1b8dfaf0, dubbo version: 3.2.7, current host: 10.1.0.45
15.512 ±(99.9%) 0.378 ms/op
                 listUser·p0.00:   4.309 ms/op
                 listUser·p0.50:   14.795 ms/op
                 listUser·p0.90:   21.791 ms/op
                 listUser·p0.95:   25.127 ms/op
                 listUser·p0.99:   36.325 ms/op
                 listUser·p0.999:  41.006 ms/op
                 listUser·p0.9999: 41.615 ms/op
                 listUser·p1.00:   41.615 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2067
  mean =     15.512 ±(99.9%) 0.378 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 211 
    [10.000, 15.000) = 860 
    [15.000, 20.000) = 706 
    [20.000, 25.000) = 181 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 19 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      4.309 ms/op
     p(50.0000) =     14.795 ms/op
     p(90.0000) =     21.791 ms/op
     p(95.0000) =     25.127 ms/op
     p(99.0000) =     36.325 ms/op
     p(99.9000) =     41.006 ms/op
     p(99.9900) =     41.615 ms/op
     p(99.9990) =     41.615 ms/op
     p(99.9999) =     41.615 ms/op
    p(100.0000) =     41.615 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.223          ops/ms
Client.existUser                       thrpt          8.379          ops/ms
Client.getUser                         thrpt          5.138          ops/ms
Client.listUser                        thrpt          1.308          ops/ms
Client.createUser                       avgt          5.256           ms/op
Client.existUser                        avgt          2.396           ms/op
Client.getUser                          avgt          5.674           ms/op
Client.listUser                         avgt         19.383           ms/op
Client.createUser                     sample   9003   3.649 ± 0.074   ms/op
Client.createUser:createUser·p0.00    sample          1.411           ms/op
Client.createUser:createUser·p0.50    sample          3.027           ms/op
Client.createUser:createUser·p0.90    sample          4.830           ms/op
Client.createUser:createUser·p0.95    sample          6.716           ms/op
Client.createUser:createUser·p0.99    sample         11.878           ms/op
Client.createUser:createUser·p0.999   sample         23.855           ms/op
Client.createUser:createUser·p0.9999  sample         25.952           ms/op
Client.createUser:createUser·p1.00    sample         25.952           ms/op
Client.existUser                      sample  13156   2.499 ± 0.080   ms/op
Client.existUser:existUser·p0.00      sample          0.295           ms/op
Client.existUser:existUser·p0.50      sample          1.739           ms/op
Client.existUser:existUser·p0.90      sample          3.958           ms/op
Client.existUser:existUser·p0.95      sample          7.505           ms/op
Client.existUser:existUser·p0.99      sample         12.810           ms/op
Client.existUser:existUser·p0.999     sample         33.292           ms/op
Client.existUser:existUser·p0.9999    sample         33.861           ms/op
Client.existUser:existUser·p1.00      sample         33.882           ms/op
Client.getUser                        sample   8521   3.847 ± 0.087   ms/op
Client.getUser:getUser·p0.00          sample          1.192           ms/op
Client.getUser:getUser·p0.50          sample          3.334           ms/op
Client.getUser:getUser·p0.90          sample          4.832           ms/op
Client.getUser:getUser·p0.95          sample          6.667           ms/op
Client.getUser:getUser·p0.99          sample         14.849           ms/op
Client.getUser:getUser·p0.999         sample         33.280           ms/op
Client.getUser:getUser·p0.9999        sample         48.169           ms/op
Client.getUser:getUser·p1.00          sample         48.169           ms/op
Client.listUser                       sample   2067  15.512 ± 0.378   ms/op
Client.listUser:listUser·p0.00        sample          4.309           ms/op
Client.listUser:listUser·p0.50        sample         14.795           ms/op
Client.listUser:listUser·p0.90        sample         21.791           ms/op
Client.listUser:listUser·p0.95        sample         25.127           ms/op
Client.listUser:listUser·p0.99        sample         36.325           ms/op
Client.listUser:listUser·p0.999       sample         41.006           ms/op
Client.listUser:listUser·p0.9999      sample         41.615           ms/op
Client.listUser:listUser·p1.00        sample         41.615           ms/op
```
